FROM php:5.6-apache

RUN docker-php-ext-install pdo pdo_mysql mysqli

COPY ./ /var/www/html/

RUN chmod -R 777 /var/www/html/uploads