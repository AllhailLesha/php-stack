FROM php:8.2-fpm-alpine

WORKDIR /var/www/php-app
    
RUN docker-php-ext-install pdo pdo_mysql

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer