# docker-nodejs

## Step-1: Run for frontend & backend container
- Access the URL http://localhost:3050 

# Docker - Essential Commands
- The below are the list of essential commands we are in need 

|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| docker-compose up | Start the container  |
| docker-compose up --build | rebuild the container  |
| docker-compose down | remove the container  |
| docker-compose ps | List all running containers |
| docker ps | List all running containers |
| docker ps -a | List all containers stopped, running |
| docker stop container-id | Stop the container which is running |
| docker start container-id | Start the container which is stopped |
| docker restart container-id | Restart the container which is running |
| docker port container-id | List port mappings of a specific container |
| docker rm container-id or name | Remove the stopped container |
| docker rm -f container-id or name| Remove the running container forcefully |
| docker pull image-info | Pull the image from docker hub repository |
| docker pull poran/springboot-helloworld-rest-api:2.0.0-RELEASE | Pull the image from docker hub repository |
| docker exec -it container-name /bin/sh | Connect to linux container and execute commands in container |
| docker rmi image-id | Remove the docker image |
| docker logout | Logout from docker hub |
| docker login -u username -p password | Login to docker hub |
| docker stats | Display a live stream of container(s) resource usage statistics |
| docker top container-id or name | Display the running processes of a container |
| docker version | Show the Docker version information |
