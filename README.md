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
docker run jjnginx:latest
```