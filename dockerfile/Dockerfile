# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER Siva "siva@example.com"
RUN apt-get update
# installing JDK
RUN apt-get install -y openjdk-7-jdk

#ADD dockertest.jar /usr/share/java/

ADD dockertest.jar /location

#VOLUME /location
EXPOSE 8080
