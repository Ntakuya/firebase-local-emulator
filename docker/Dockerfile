FROM ubuntu:20.10

RUN apt-get update -y

RUN apt-get install apt-utils default-jre default-jdk curl -y

RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
RUN apt-get install -y nodejs

RUN npm install -g firebase-tools
