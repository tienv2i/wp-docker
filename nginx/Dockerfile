FROM nginx:latest

COPY certs/cert.pem /etc/ssl/certs/
COPY certs/key.pem /etc/ssl/private/

COPY default-ssl.conf /etc/nginx/conf.d/default-ssl.conf

EXPOSE 443