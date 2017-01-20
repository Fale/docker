# Fale docker
All Dockerfiles here present are comipled at https://hub.docker.com/u/fale/

## Build example
image=awscli
version=1.11.34
docker build -t docker.io/fale/${image}:${version} ${image}
docker push docker.io/fale/${image}:${version}
docker tag docker.io/fale/${image}:${version} docker.io/fale/awscli:latest
docker push docker.io/fale/awscli:latest

## Login
docker login 

