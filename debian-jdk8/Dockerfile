FROM debian:jessie

MAINTAINER omartech.com <sonyfe25cp@gmail.com>

RUN apt-get update && \
    apt-get install -y wget
RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u60-b27/jdk-8u60-linux-x64.tar.gz

RUN tar zxvf jdk-8u60-linux-x64.tar.gz


RUN echo "export JAVA_HOME=/jdk1.8.0_60" >> ~/.bashrc
RUN echo "export PATH=$PATH:/jdk1.8.0_60/bin" >> ~/.bashrc


RUN rm /jdk-8u60-linux-x64.tar.gz

#docker build -t "omartech/debian-jessie-jdk8" .
