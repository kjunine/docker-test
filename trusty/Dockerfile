FROM ubuntu:trusty
MAINTAINER Daniel Ku "kjunine@gmail.com"
ENV REFRESHED_AT 2014-09-02

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y git wget curl

#RUN apt-get install -y build-essential
#RUN apt-get install -y software-properties-common python-software-properties

ENV HOME /root
WORKDIR /root
