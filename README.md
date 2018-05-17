# JJ Azure Container Nginx

This repo describes how to create new Nginx image.

Nginx Docker image documentation on [dockerhub](https://hub.docker.com/_/nginx/).

## Build image

```bash
docker build . -t jjnginx:latest

docker images
```

## Run container

```bash
docker run -d -p 8080:80 jjnginx:latest

docker ps
```

Check in browser http://localhost:8080/

## Connect into container

```bash
docker exec -it 7c "/bin/bash"
``` 
