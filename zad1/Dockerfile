FROM ubuntu:20.04

RUN apt-get update && apt-get install -y

#Java
RUN apt-get install openjdk-11-jdk -y

RUN apt-get install curl zip unzip git nano -y

#Kotlin
RUN curl -s https://get.sdkman.io | bash
RUN /bin/bash -c "source $HOME/.sdkman/bin/sdkman-init.sh && sdk install kotlin && sdk install gradle"

EXPOSE 8000
