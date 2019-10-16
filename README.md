# Dockerized 1000kit wildfly backend image

This repository contains `JBoss Wildfly` image and aditional drivers(postgres)


### Installed versions:

 Wildfly 17.0.0.Final

### Availability

The `Dockerfile` is available in the `master` branch and is built in the Docker HUB as `1000kit/wildfly-backend:latest`.

## Build Image

Take a Dockerfile and build with the default arguments:

~~~~
$ docker build -t 1000kit/wildfly-backend .
~~~~

or simply use the `build.sh` script

##RUN

~~~~
$ docker run -it 1000kit/wildfly-backend
~~~~

