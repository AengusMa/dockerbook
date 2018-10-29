#docker搭建nginx静态网站demo
FROM ubuntu:16.04
LABEL maintainer="mwljndx@163.com"
ENV REFRESHED_AT 2018-10-29

RUN apt-get -qq update && apt-get -qq install nginx

RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/

EXPOSE 80