FROM php:7.0-apache
RUN docker-php-ext-install pdo_mysql
COPY beta.php /var/www/html/index.php
EXPOSE 80