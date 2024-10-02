FROM php:8.3.12-apache

RUN apt update \
    && docker-php-ext-install pdo_mysql

COPY src/ /var/www/html/
