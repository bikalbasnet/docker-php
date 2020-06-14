FROM php:7.1.3-fpm
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" \
	&& php composer-setup.php --install-dir=/usr/local/bin --filename=composer \
	&& rm composer-setup.php
RUN apt-get update && apt-get install -y git zip
WORKDIR /usr/src/myapp