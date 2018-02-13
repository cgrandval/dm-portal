FROM php:7.1-alpine
LABEL maintainer="cgrandval@darkmira.com"

RUN docker-php-ext-install pdo_mysql

RUN apk --update add git && \
    rm -rf /tmp/* /var/cache/apk/

RUN git clone https://github.com/Eficode/wait-for.git /usr/local/wait-for
