FROM ubuntu:latest

RUN export DEBIAN_FRONTEND=noninteractive
RUN echo "DEBIAN_FRONTEND=noninteractive" >> /root/.bashrc
RUN apt update
RUN apt -y upgrade
RUN apt -y install curl wget
RUN apt -y install openjdk-8-jdk
RUN apt -y install nodejs npm
RUN npm install n -g
RUN npm install node-sass@8 -g
RUN n 14