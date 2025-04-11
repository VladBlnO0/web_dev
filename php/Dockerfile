FROM php:7.3-apache

RUN apt-get update && \
    apt-get install -y libpng-dev && \
    docker-php-ext-install mysqli json

EXPOSE 80