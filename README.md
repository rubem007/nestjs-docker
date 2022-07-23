
## Start Commands for docker-compose file
Builds, (re)creates, starts, and attaches to containers for a service.
`docker-compose up`

## Start Commands for Docker
Build your image:
`docker build -t <user>/project-name .`

Run:
`docker run -p 3000:3000 <<user>/project-name>`

For Example:
`docker build -t rubemnascimento81/nestjs-docker .`
`docker run -p 3000:3000 rubemnascimento81/nestjs-docker`

Basic Docker Commands:
List your docker images: `docker images`
Remove a image: `docker rmi -f IMAGE_NAME`
List your running containers: `docker ps`
Stop container: `docker stop CONTAINE_ID`
Remove container: `docker rm -f CONTAINER_ID`
