# spring-boot-docker
Basic App which integrates Spring Boot and Docker

## It was created using the following tutorial
https://spring.io/guides/gs/spring-boot-docker/

## Commands executed on Ubuntu 20.04
```console
sudo snap install docker
docker pull openjdk
```


# To run a Open JDK container (for playground porpouses):
To start an instance:
```console
sudo docker run --name openjdk -it openjdk /bin/sh
sh-4.4# java -version
openjdk version "18.0.1.1" 2022-04-22
```





```console
docker exec -it mycontainer /bin/sh
```

# Resource links
How to use the OpenJDK image
https://hub.docker.com/_/openjdk
