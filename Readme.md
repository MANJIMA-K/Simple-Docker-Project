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