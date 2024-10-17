# to have a slim version how ? 
FROM debian:bullseye 


RUN apt update
RUN apt upgrade -y
RUN apt install nginx -y
RUN apt install vim -y
RUN apt install curl -y
RUN mkdir -p /etc/nginx/ssl
RUN apt install OpenSSL -y
# RUN openssl req -x509 -nodes -out /etc/nginx/ssl/inception.crt -keyout /etc/nginx/ssl/inception.key -subj "/C=FR/ST=IDF/L=Canada/O=42/OU=42/CN=mnshimiy.42.fr/UID=mnshimiy"
# RUN mkdir -p /var/run/nginx

# COPY conf/nginx.conf /etc/nginx/n.conf 