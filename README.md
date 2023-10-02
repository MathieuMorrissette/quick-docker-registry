cd certs
openssl req -x509 -nodes -newkey rsa:4096 -keyout domain.key -out domain.crt -days 365
cd ..
docker compose up