FROM kjunine/trusty
MAINTAINER Daniel Ku "kjunine@gmail.com"
ENV REFRESHED_AT 2014-09-02

RUN apt-get install -y redis-server redis-tools

EXPOSE 6379

ENTRYPOINT ["/usr/bin/redis-server"]
