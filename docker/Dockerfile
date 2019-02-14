FROM nimmis/apache-php5
MAINTAINER prc2k10 <prc2k10@googlemail.com>

COPY 000-default.conf /etc/apache2/sites-available/000-default.conf

RUN a2enmod rewrite

EXPOSE 80
EXPOSE 443
