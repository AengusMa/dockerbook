FROM jamtur01/redis
LABEL maintainer="mwljndx@163.com"
ENV REFRESHED_AT 2018-11-01

ENTRYPOINT [ "redis-server", "--protected-mode no", "--logfile /var/log/redis/redis-replica.log", "--slaveof redis_primary 6379" ]