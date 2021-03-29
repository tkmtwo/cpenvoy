

FROM cnfldemos/cp-server-connect-datagen:0.4.0-6.1.0


USER root

COPY --chown=appuser:appuser src/appuser-bin /home/appuser/bin
COPY --chown=appuser:appuser src/pki /etc/confluent/pki
COPY --chown=appuser:appuser src/envoy /home/appuser/envoy

RUN yum -y update
RUN yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
RUN yum install -y yum-utils
RUN yum-config-manager --add-repo https://www.getenvoy.io/linux/rhel/tetrate-getenvoy.repo


RUN yum -y install yum-utils less vim nc jq getenvoy-envoy
RUN yum clean all


USER appuser

CMD "/home/appuser/bin/startcontainer"
