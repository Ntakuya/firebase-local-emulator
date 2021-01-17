FROM ubuntu:20.10

WORKDIR /api

COPY . /api

RUN apt-get update -y

RUN apt-get install apt-utils default-jre default-jdk curl -y

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get install -y nodejs

RUN npm install -g firebase-tools

ENV HOST 0.0.0.0