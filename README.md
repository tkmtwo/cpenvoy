# cpenvoy
Confluent Platform with Envoy Proxies




Build the extended connect image:
docker build -f src/connect/Dockerfile -t cpenvoy/connect .


Bring up everything up/down:
docker-compose up -d
docker-compose stop

Bring up a single image (includes dependencies):
docker-compose up connect1

Get a terminal:
docker exec -it connect2 bash


Clean the kitchen:
docker system prune

Inspect an image:
docker image inspect 1cc232ed359c


envoy --log-path envoy.log -c envoy.yaml

curl --verbose --cacert kc-ca.crt --cert kc-worker.crt --key kc-worker.key --pass mypass     https://connect1:8443
curl --verbose --cacert kc-ca.crt                                           --user ok:test1  https://connect1:443

curl --verbose --cacert kc-ca.crt --user ok:test1  https://connect1:443


Localhost [Control Center](http://localhost:9021/)
Localhost [ksqldb Server](http://localhost:8088/)
Localhost [Connect1](http://localhost:10443/)
Localhost [Connect2](http://localhost:11443/)
Localhost [REST Proxy](http://localhost:8082/)
Localhost [Schema Registry](http://localhost:8081)


