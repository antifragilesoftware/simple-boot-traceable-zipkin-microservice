# Sample Spring Boot Service with Tracing using Zipkin

## To Build into Docker using Maven

First make sure you're running in an environment that has docker available to you. Then execute:

$ ./mvnw package docker:build

Once completed you will have an antifragilesoftware/simple-boot-traceable-zipkin-microservice image available, as seen by executing:

$ docker images

```
REPOSITORY                         TAG                 IMAGE ID            CREATED             SIZE
antifragilesoftware/simple-boot-traceable-zipkin-microservice   latest              6efd07dc12fc        5 seconds ago       667.1 MB
```
