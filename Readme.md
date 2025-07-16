This is a simple dockerized node.js project

## Key commands

docker login

docker build -t my-node-app .

docker build -t my-node-app:v1 .

docker images

docker run -p 3000:3000

docker ps -a

docker stop containerName

docker run -d -p 3000:3000 image-name

docker logs containerName

docker run -d -p 3000:3000 --name newContainerName image-name

docker exec containerName ls

docker exec it containerName bash

ls

cat fileName

docker volume ls

docker volume create myvol

docker volume inspect myvol

docker volume rm myvol

docker volume prune

docker network ls

docker network create mynet

docker network inspect bridge

docker network rm mynet

docker network prune