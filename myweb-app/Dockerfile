FROM php:7.2-apache
LABEL  "MAINTAINER"="Robiyanto"  \
        "EMAIL"="mr.robiyanto@gmail.com"

RUN apt-get update && apt-get install libstdc++5 -y
RUN docker-php-ext-install pdo pdo_mysql

COPY file-web /var/www/html/