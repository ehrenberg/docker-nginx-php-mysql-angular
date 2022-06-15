FROM phpdockerio/php:8.1-fpm
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
		php8.1-opcache \
        php8.1-http \
        php8.1-raphf \
        php8.1-imap \ 
        php8.1-memcache \ 
        php8.1-memcached \ 
        php8.1-mysql \ 
        php8.1-oauth \ 
        php8.1-xdebug \ 
        php8.1-yaml; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
