FROM kjunine/trusty
MAINTAINER Daniel Ku "kjunine@gmail.com"
ENV REFRESHED_AT 2014-09-02

RUN apt-get install -y man

RUN curl https://raw.githubusercontent.com/creationix/nvm/v0.14.0/install.sh | bash

RUN /bin/bash -c '. ~/.nvm/nvm.sh && nvm install 0.10'
RUN ln -s ~/.nvm/current/bin/node /usr/bin/node && ln -s ~/.nvm/current/bin/npm /usr/bin/npm

RUN npm install -g pm2
