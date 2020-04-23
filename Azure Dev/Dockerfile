#
# Creation of a Dockerfile
#
FROM ubuntu:latest
MAINTAINER Rajesh Vuppu "vuppurajesh.in@outlook.com"

RUN apt-get update
RUN apt-get install -y python python-pip wget
RUN pip install Flask
RUN apt-get install -y jdk-latest
RUN apt-get install -y tomcat

RUN   echo "Welcome to Sonata Software" >> /var/lib/tomcat/sonata.html



WORKDIR /home