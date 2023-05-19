Docker:



CONTAINERS:
Containers are an abstraction at the app layer that
packages code and dependencies together.
Multiple containers can run on the same machine and share the
OS kernel with other containers, each running as isolated processes in user space.


Benefits:
Run container in seconds instead of minutes
Less resources results less disk space
Uses less Memory
Does not need full OS
Deployment
Testing



Docker Image:
Image is a template for creating an environment of your Choice
Snapshot
Has everything need to run your Apps
OS, Software, App Code



Container:
Running instance of an Image
![Alt Text](/container.png)
https://github.com/MayurPondkule/Docker/blob/main/container.png?raw=true


Volumes
Allows sharing of data. Files & Folders
Between host and container
Between containers


docker
docker – -version
docker ps (process status)


1.Container Management:

docker run: Create and start a new container based on an image.
docker start: Start one or more stopped containers.
docker stop: Stop one or more running containers.
docker restart: Restart one or more containers.
docker pause: Pause processes in one or more containers.
docker unpause: Unpause processes in one or more containers.
docker rm: Remove one or more containers.
docker ps: List running containers.
docker ps -a: List all containers (including stopped ones).



2.Image Management:

docker pull: Download an image from a registry.
docker build: Build a new image from a Dockerfile.
docker push: Push an image to a registry.
docker images: List available images.
docker rmi: Remove one or more images.


3.Volume Management:

docker volume create: Create a new volume.
docker volume ls: List volumes.
docker volume inspect: Display detailed information about a volume.
docker volume rm: Remove one or more volumes.
