### docker-introduction

## Build container
`docker build -t [image name] -e [environment if required] -d [start automatically] -p [port] .`

## Run image
`docker run [Image-ID] -d <detached mode> -p <local-port>:<docker-port>`

## Show all container
`docker container ls -a`

## Show all images
`docker image ls`

## Create a tag
`docker tag [image ID] [username]/[imagename]`

## Push image
`docker push [username]/[imagename]`

## RUN an EXEC command (Run docker container with interactive mode):
`docker exec -it [Container-Name] bash`

## Remove a container
`docker container rm <ContainerIDs>`

## Remove all stopped containers
`docker container prune`

## Remove images
`docker image rm <ContainerIDs>`

## Remove all unused docker
`docker system prune`
`docker system prune --volumes`

## Remove unused image
`docker image prune -a`


## Create a network
`docker network create <network-name>`

## SAVE docker image:

`docker save [Image-Name] > [Image-Name.tar]`

## LOAD docker image:
`docker load --input [Image-Name.tar]`
