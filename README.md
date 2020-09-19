### docker-introduction

## Build container

`docker build -t [image name] -e [environment if required] -d [start automatically] -p [port]`

## Run image
`docker run [Image-ID] -d <detached mode> -p <port> [port number]`

## Remove all unused docker

`docker system prune`

`docker system prune --volumes`

## Show all container

`docker container ls -a`

## Remove a container

`docker container rm <ContainerIDs>`

## Remove all stopped containers

`docker container prune`

## Show all images

`docker image ls`

## Remove images

`docker image rm <ContainerIDs>`

## Remove unused image

`docker image prune -a`

## Create a tag

`docker tag [image ID] [username]/[imagename]`

## Push image

`docker push [username]/[imagename]`

## RUN an EXEC command (Run docker container with interactive mode):

`docker exec -it [Container-Name] bash`

## SAVE docker image:

`docker save [Image-Name] > [Image-Name.tar]`

## LOAD docker image:

`docker load --input [Image-Name.tar]`
