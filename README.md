# spring-boot-docker
Basic App which integrates Spring Boot and Docker

# It was created using the following tutorial
https://spring.io/guides/gs/spring-boot-docker/







# Commands executed on Ubuntu 20.04
```console
sudo snap install docker
docker pull openjdk
```


# To run a Open JDK container (for play porpouses):
To start an instance:
```console
docker run — name myopenjdkcontainer -d openjdk tail -f /dev/null
```

```console
docker exec -it mycontainer /bin/sh
```
#Resource links
How to use the image
https://hub.docker.com/_/openjdk
