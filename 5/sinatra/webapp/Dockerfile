# 网站功能将字符串转为json（post请求）
FROM ubuntu:16.04
LABEL maintainer="mlwjndx@163.com"
ENV REFRESHED_AT 2018-10-29

RUN apt-get update && apt-get -y install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis

RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD [ "/opt/webapp/bin/webapp" ]