CA cert and keys.
Key passphrase is "capass"



===============================================================
openssl x509 -in src/pki/kc-ca.crt -text
===============================================================
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            75:c6:a1:d8:b9:e7:77:bb:68:90:1a:60:02:50:4d:d9:c8:76:c4:44
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: CN = kc-ca
        Validity
            Not Before: Mar 28 01:25:53 2021 GMT
            Not After : Mar 28 01:25:53 2022 GMT
        Subject: CN = kc-ca
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                RSA Public-Key: (2048 bit)
                Modulus:
                    00:c5:2e:3e:88:27:2a:74:d8:65:80:4c:ee:78:12:
                    3a:08:02:f0:42:c8:f1:66:14:3a:b6:f1:9b:fb:b9:
                    3b:a2:58:7d:3d:d7:b0:47:64:f6:34:17:a7:ec:22:
                    a3:9c:3e:9c:00:01:d7:0f:fc:8a:0d:23:64:50:6d:
                    a7:b8:28:4e:fd:84:eb:b3:ca:12:8d:8a:23:d8:c2:
                    96:64:e1:b8:66:2c:1b:fa:7e:63:0f:07:87:f5:38:
                    f8:b5:b1:9d:07:48:37:76:cb:1b:6e:16:dc:d5:ea:
                    ac:e0:5f:ee:ca:22:11:ba:32:7c:3a:29:bb:bd:6c:
                    6c:75:b6:8a:cc:57:74:fb:ac:7c:6c:a7:53:be:cb:
                    23:5a:33:15:f3:43:a6:4d:ea:9d:6f:4b:05:7e:bc:
                    af:71:d3:94:ff:b8:61:d7:97:8e:81:d0:1d:a4:f5:
                    43:84:c3:07:cb:b7:9a:d3:c5:e6:da:b6:6d:b8:f4:
                    27:0f:6a:34:4c:8f:29:33:97:e3:5d:d4:44:62:40:
                    7c:5f:48:60:f0:e7:20:ac:bc:1b:3e:17:db:07:1c:
                    e3:06:97:f8:f0:89:7e:08:08:1a:91:1d:c1:57:3f:
                    7c:0e:bc:6e:1a:6f:d8:83:83:4e:c1:b8:68:64:1e:
                    26:4e:7e:c3:c1:c3:6c:96:d0:ae:07:35:f2:79:c4:
                    2f:d9
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Subject Key Identifier: 
                37:A7:91:FE:14:79:5D:0E:BD:7D:13:95:11:23:F5:E6:C7:78:CA:0F
            X509v3 Authority Key Identifier: 
                keyid:37:A7:91:FE:14:79:5D:0E:BD:7D:13:95:11:23:F5:E6:C7:78:CA:0F

            X509v3 Basic Constraints: critical
                CA:TRUE
    Signature Algorithm: sha256WithRSAEncryption
         6c:19:ad:5f:69:7a:eb:11:2b:f4:2b:dd:3d:24:bd:35:fa:b0:
         40:5d:aa:e9:ee:f9:99:46:c8:e6:cb:b8:01:af:8f:da:dd:78:
         50:b1:87:d8:90:05:dd:5f:1a:3c:bf:a7:34:02:ee:7b:16:d9:
         e6:28:76:eb:18:6c:a7:a9:3d:09:cd:00:bb:b8:b2:46:db:7c:
         2d:e2:78:e7:ae:d9:34:83:33:95:52:86:6e:1f:8b:9a:23:d4:
         7f:b9:c6:df:df:a4:eb:af:90:5a:6d:6c:ae:f8:21:c2:9c:7f:
         e4:74:10:57:f8:2f:09:08:24:16:ea:fc:60:35:dd:83:88:2e:
         df:fd:d9:d3:94:c5:f1:f2:1b:ce:6e:29:04:ba:0b:c7:25:4e:
         de:d0:67:71:aa:c3:c9:40:1e:69:29:39:8d:cf:c0:55:59:8c:
         38:c1:34:6a:e4:e2:d3:be:b3:96:53:5a:84:7f:84:31:01:87:
         59:e9:8a:44:a8:ac:2a:aa:45:26:e3:08:ab:ea:59:9a:0f:05:
         6f:f5:be:bd:d0:c0:c7:ec:bf:60:df:b2:21:da:1b:ad:5d:8f:
         87:73:23:73:20:56:48:42:de:80:de:75:06:b9:70:0f:d2:a5:
         f1:ec:d7:ee:a2:a7:74:ff:98:60:03:c2:84:4a:22:2f:a6:4c:
         47:65:b3:4b
-----BEGIN CERTIFICATE-----
MIIDATCCAemgAwIBAgIUdcah2Lnnd7tokBpgAlBN2ch2xEQwDQYJKoZIhvcNAQEL
BQAwEDEOMAwGA1UEAwwFa2MtY2EwHhcNMjEwMzI4MDEyNTUzWhcNMjIwMzI4MDEy
NTUzWjAQMQ4wDAYDVQQDDAVrYy1jYTCCASIwDQYJKoZIhvcNAQEBBQADggEPADCC
AQoCggEBAMUuPognKnTYZYBM7ngSOggC8ELI8WYUOrbxm/u5O6JYfT3XsEdk9jQX
p+wio5w+nAAB1w/8ig0jZFBtp7goTv2E67PKEo2KI9jClmThuGYsG/p+Yw8Hh/U4
+LWxnQdIN3bLG24W3NXqrOBf7soiEboyfDopu71sbHW2isxXdPusfGynU77LI1oz
FfNDpk3qnW9LBX68r3HTlP+4YdeXjoHQHaT1Q4TDB8u3mtPF5tq2bbj0Jw9qNEyP
KTOX413URGJAfF9IYPDnIKy8Gz4X2wcc4waX+PCJfggIGpEdwVc/fA68bhpv2IOD
TsG4aGQeJk5+w8HDbJbQrgc18nnEL9kCAwEAAaNTMFEwHQYDVR0OBBYEFDenkf4U
eV0OvX0TlREj9ebHeMoPMB8GA1UdIwQYMBaAFDenkf4UeV0OvX0TlREj9ebHeMoP
MA8GA1UdEwEB/wQFMAMBAf8wDQYJKoZIhvcNAQELBQADggEBAGwZrV9peusRK/Qr
3T0kvTX6sEBdqunu+ZlGyObLuAGvj9rdeFCxh9iQBd1fGjy/pzQC7nsW2eYodusY
bKepPQnNALu4skbbfC3ieOeu2TSDM5VShm4fi5oj1H+5xt/fpOuvkFptbK74IcKc
f+R0EFf4LwkIJBbq/GA13YOILt/92dOUxfHyG85uKQS6C8clTt7QZ3Gqw8lAHmkp
OY3PwFVZjDjBNGrk4tO+s5ZTWoR/hDEBh1npikSorCqqRSbjCKvqWZoPBW/1vr3Q
wMfsv2DfsiHaG61dj4dzI3MgVkhC3oDedQa5cA/SpfHs1+6ip3T/mGADwoRKIi+m
TEdls0s=
-----END CERTIFICATE-----
