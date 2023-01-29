FROM ubuntu:latest

MAINTAINER Carl "cpjjpeters@gmail.com"

RUN apt-get update && apt-get install -y openjdk-11-jdk

WORKDIR /usr/local/bin/
ADD simple-service.jar .

ENTRYPOINT ["java", "-jar", "simple-service.jar"]
