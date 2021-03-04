FROM php:7.3

RUN apt-get update && apt-get install -y git zip

RUN docker-php-ext-install pdo_mysql

COPY --from=composer:2.0 /usr/bin/composer /usr/local/bin