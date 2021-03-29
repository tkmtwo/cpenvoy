Worker node cert and keys.
Key passphrase is "mypass"





======================================================
openssl x509 -in src/pki-laptop/kc-worker.crt -text
======================================================
Certificate:
    Data:
        Version: 1 (0x0)
        Serial Number:
            76:f1:3a:89:f1:92:93:8d:06:0d:05:4a:9c:8f:2d:8a:d0:bb:03:5b
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: CN = kc-ca
        Validity
            Not Before: Mar 28 12:00:43 2021 GMT
            Not After : Mar 28 12:00:43 2022 GMT
        Subject: CN = localhost
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                RSA Public-Key: (2048 bit)
                Modulus:
                    00:bd:85:93:63:76:dc:da:9e:f2:59:90:e4:3a:cb:
                    24:35:2c:32:af:84:06:fc:2d:f0:29:5a:19:08:61:
                    d8:2e:7d:06:72:59:07:24:31:d3:33:f3:4f:6f:d9:
                    04:0f:87:5f:68:d0:a3:be:c8:04:be:fa:1e:38:ce:
                    28:6b:cc:4e:f5:21:6c:4c:57:9e:68:a1:15:83:f6:
                    2c:d7:98:22:5c:1d:e4:91:40:e7:4e:21:ac:dc:9c:
                    33:62:22:0c:74:1d:5f:5c:65:ea:90:19:f4:39:01:
                    c3:39:bc:2d:05:21:3f:44:fd:19:e1:0b:4b:4b:c9:
                    a4:7e:fb:97:a7:0a:71:9a:76:8d:3f:2d:e1:9b:06:
                    57:76:44:88:60:b6:9a:2a:f5:3c:32:15:1c:b1:1c:
                    96:41:d6:d9:ba:a7:16:12:f5:d9:23:29:55:d6:7e:
                    eb:9d:62:bc:ed:6b:2a:c0:e2:c0:a0:cb:26:67:2c:
                    99:9f:fe:ca:52:a3:a5:fc:87:ac:d0:64:e2:8b:03:
                    23:2b:5d:aa:1d:1f:63:0e:84:71:7a:41:9d:09:80:
                    0e:7d:08:74:13:d9:36:f0:03:b9:2d:95:e3:c3:f6:
                    22:41:6a:24:f7:71:f7:65:44:20:25:79:45:86:d1:
                    00:fa:22:69:c7:fa:83:e2:36:e8:7f:6d:0a:e8:bf:
                    b9:69
                Exponent: 65537 (0x10001)
    Signature Algorithm: sha256WithRSAEncryption
         83:5b:bf:f1:00:9d:1d:04:36:51:e3:fb:50:d8:46:aa:75:e8:
         0b:40:8c:f6:5f:26:16:a1:08:07:65:42:34:57:10:5b:a5:ce:
         b8:44:60:b7:f8:be:c2:fd:e1:44:96:5c:7f:4d:a1:c6:b5:15:
         7c:b7:13:6c:14:17:b9:68:d9:78:65:60:09:09:ed:c2:b0:b7:
         ce:60:49:6e:fe:86:e1:f7:21:bd:f9:b1:de:fb:f1:b6:6b:56:
         cd:78:35:2f:13:ee:d0:0b:67:e2:db:df:c6:8a:9a:0e:40:11:
         f4:97:c1:79:79:18:5a:4b:bc:c2:f5:69:32:42:07:bf:8b:26:
         c4:53:3b:2e:29:60:09:c2:61:c9:0f:86:aa:de:0c:71:4f:dd:
         6e:46:a2:ea:2c:6e:2a:31:da:6a:f8:2b:f8:96:39:c9:31:68:
         a1:75:8b:0e:f1:ca:a7:e4:58:15:47:08:0e:2c:aa:4f:21:08:
         a2:c6:ab:29:f9:33:d1:08:0a:7b:09:cf:a6:de:57:0a:d5:46:
         4c:34:4c:2e:e5:7e:56:3c:16:69:98:ef:03:e3:ee:42:b9:d7:
         8b:19:19:1d:4f:e6:bf:9a:cd:d3:b1:d5:a3:82:60:37:24:f7:
         6a:a1:87:58:37:15:2d:4d:58:5b:86:b4:9f:be:26:a1:44:e2:
         3c:b0:3f:e2
-----BEGIN CERTIFICATE-----
MIICqzCCAZMCFHbxOonxkpONBg0FSpyPLYrQuwNbMA0GCSqGSIb3DQEBCwUAMBAx
DjAMBgNVBAMMBWtjLWNhMB4XDTIxMDMyODEyMDA0M1oXDTIyMDMyODEyMDA0M1ow
FDESMBAGA1UEAwwJbG9jYWxob3N0MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIB
CgKCAQEAvYWTY3bc2p7yWZDkOsskNSwyr4QG/C3wKVoZCGHYLn0GclkHJDHTM/NP
b9kED4dfaNCjvsgEvvoeOM4oa8xO9SFsTFeeaKEVg/Ys15giXB3kkUDnTiGs3Jwz
YiIMdB1fXGXqkBn0OQHDObwtBSE/RP0Z4QtLS8mkfvuXpwpxmnaNPy3hmwZXdkSI
YLaaKvU8MhUcsRyWQdbZuqcWEvXZIylV1n7rnWK87WsqwOLAoMsmZyyZn/7KUqOl
/Ies0GTiiwMjK12qHR9jDoRxekGdCYAOfQh0E9k28AO5LZXjw/YiQWok93H3ZUQg
JXlFhtEA+iJpx/qD4jbof20K6L+5aQIDAQABMA0GCSqGSIb3DQEBCwUAA4IBAQCD
W7/xAJ0dBDZR4/tQ2EaqdegLQIz2XyYWoQgHZUI0VxBbpc64RGC3+L7C/eFEllx/
TaHGtRV8txNsFBe5aNl4ZWAJCe3CsLfOYElu/obh9yG9+bHe+/G2a1bNeDUvE+7Q
C2fi29/GipoOQBH0l8F5eRhaS7zC9WkyQge/iybEUzsuKWAJwmHJD4aq3gxxT91u
RqLqLG4qMdpq+Cv4ljnJMWihdYsO8cqn5FgVRwgOLKpPIQiixqsp+TPRCAp7Cc+m
3lcK1UZMNEwu5X5WPBZpmO8D4+5CudeLGRkdT+a/ms3TsdWjgmA3JPdqoYdYNxUt
TVhbhrSfviahROI8sD/i
-----END CERTIFICATE-----
