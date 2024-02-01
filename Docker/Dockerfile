FROM php:8.1-apache-bookworn

WORKDIR /var/www/html

RUN apt update && \
    apt -y install git && \
    apt clean && \
    git clone https://github.com/JavierCedres/JavierMarceloCG-SSG.git . && \
    chown -R root:root .
EXPOSE 80