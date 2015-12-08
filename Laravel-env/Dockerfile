FROM node:latest
RUN apt-get update
RUN apt-get install -y vim git build-essential php5 php5-sqlite
RUN npm install -g bower
RUN php -r "readfile('https://getcomposer.org/installer');" | php
RUN mv composer.phar /usr/local/bin/composer
RUN composer global require "laravel/installer=~1.1"
RUN export PATH=$PATH:~/.composer/vendor/bin
