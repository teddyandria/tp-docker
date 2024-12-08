FROM php:5.6-apache

RUN docker-php-ext-install mysqli
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf

COPY ./ /var/www/html/

RUN chmod -R 777 /var/www/html/uploads