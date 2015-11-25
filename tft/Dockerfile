FROM ubuntu:latest
RUN apt-get update
RUN apt-get install -y vim git build-essential php5 php5-sqlite node npm
RUN npm install bower
RUN php -r "readfile('https://getcomposer.org/installer');" | php
