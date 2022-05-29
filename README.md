# spring-boot-docker
Basic App which integrates Spring Boot and Docker

## It was created using the following tutorial
https://spring.io/guides/gs/spring-boot-docker/

## How to execute it (tested on Ubuntu 20.04)
```console
sudo snap install docker
docker pull openjdk
docker build -t springio/gs-spring-boot-docker .
sudo docker run -p 8080:8080 springio/gs-spring-boot-docker
```
Note: this is not production ready code, is just for educational porpouses, for production it will not be executed as sudo.


# To run a Open JDK container (for playground porpouses):
To start an instance:
```console
sudo docker run --name openjdk -it openjdk /bin/sh
sh-4.4# java -version
openjdk version "18.0.1.1" 2022-04-22
```

# Resource links
How to use the OpenJDK image
https://hub.docker.com/_/openjdk
