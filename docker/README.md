# Docker

Install latest version
> curl -sSL https://get.docker.com/ | sh

Delete all containers
> docker rm $(docker ps -a -q)

Delete all images
> docker rmi $(docker images -q)

Access container terminal
> docker exec -it CONTAINER_NAME bash

If you have issue like:
> ERROR: client and server don't have same version (client : 1.21, server: 1.18)

Use this command to fix it:
> export COMPOSE_API_VERSION=1.18
