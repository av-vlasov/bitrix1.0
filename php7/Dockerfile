FROM 7-fpm

MAINTAINER skazochnik2007

ADD ./php.ini /etc/php/7.1/fpm/conf.d/90-php.ini
ADD ./php.ini /etc/php/7.1/cli/conf.d/90-php.ini

RUN usermod -u 1000 www-data

WORKDIR "/var/www/bitrix"

EXPOSE 9000
