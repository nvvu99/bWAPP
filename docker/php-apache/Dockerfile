FROM php:5.6-apache

RUN docker-php-ext-install mysqli

COPY ./apache2.conf /etc/apache2/apache2.conf

EXPOSE 80
