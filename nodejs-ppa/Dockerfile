FROM kjunine/trusty
MAINTAINER Daniel Ku "kjunine@gmail.com"
ENV REFRESHED_AT 2014-09-02

RUN apt-get install -y software-properties-common python-software-properties

RUN add-apt-repository ppa:chris-lea/node.js
RUN apt-get update

RUN apt-get install -y nodejs

RUN npm install -g pm2
