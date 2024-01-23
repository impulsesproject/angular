FROM node:slim

RUN apt update -y && apt upgrade -y
RUN apt install -y git

RUN npm install -g npm@latest
RUN npm install -g @angular/cli

WORKDIR /workspace
COPY . .
