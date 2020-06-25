### SSL generation

[source](https://medium.com/@richardr39/using-angular-cli-to-serve-over-https-locally-70dab07417c8)
[source1](https://medium.com/@rubenvermeulen/running-angular-cli-over-https-with-a-trusted-certificate-4a0d5f92747a)

in terminal:
openssl req -new -x509 -newkey rsa:2048 -sha256 -nodes -keyout localhost.key -days 3560 -out localhost.crt -config certificate.cnf
