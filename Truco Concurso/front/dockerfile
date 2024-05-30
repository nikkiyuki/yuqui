FROM php:7.4-apache
RUN apt update
RUN apt install apache2 -y
COPY . /var/www/html/
EXPOSE 80
CMD apachectl -D FOREGROUND