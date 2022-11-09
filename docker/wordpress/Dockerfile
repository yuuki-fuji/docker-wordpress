# syntax=docker/dockerfile:1
FROM php:7.4-apache

RUN apt-get update
RUN apt-get install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev libzip-dev zip libicu-dev
RUN docker-php-ext-install pdo pdo_mysql mysqli iconv gd
