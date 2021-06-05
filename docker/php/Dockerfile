ARG php_version

FROM php:${php_version}

RUN docker-php-ext-install mysqli pdo pdo_mysql

RUN apt-get update && apt-get install -y
