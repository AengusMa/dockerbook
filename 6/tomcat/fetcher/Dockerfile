# 获取war文件
FROM ubuntu:16.04
LABEL maintainer="mwljndx@163.com"
ENV REFRESHED_AT 2018-11-01

RUN apt-get -qq update
RUN apt-get -qq install wget

VOLUME [ "/var/lib/tomcat7/webapps/" ]
WORKDIR /var/lib/tomcat7/webapps/

ENTRYPOINT [ "wget" ]
CMD [ "--help" ]