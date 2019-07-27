# Download base image Ubuntu 18.04
FROM ubuntu:18.04
# Update Ubuntu sources
RUN sudo apt update
# Install nginx, php-fpm and supervisord from ubuntu repository
RUN apt-get install -y nginx php7.0-fpm supervisor && \
    rm -rf /var/lib/apt/lists/*
