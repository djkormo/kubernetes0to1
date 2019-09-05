FROM php:7.2-apache

COPY ./ /symfony/

RUN rm -rf /var/www/html && ln -s /symfony/public /var/www/html
RUN a2enmod rewrite