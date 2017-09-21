# using official image https://hub.docker.com/_/openjdk/
# Reference - https://docs.docker.com/engine/reference/builder/
FROM openjdk:9-jdk

COPY default-configs/default-bashrc /root/.bashrc

RUN apt-get update && \
  apt-get install -y \
    maven

# change the default Java version
#RUN update-java-alternatives --set java-1.9.0-openjdk-amd64

