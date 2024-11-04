
## What is Docker?
Docker is an open-source containerization platform by which you can pack your application and all its dependencies into a standardized unit called a container. Containers are light in weight which makes them portable and they are isolated from the underlying infrastructure and from each other container. You can run the docker image as a docker container in any machine where docker is installed without depending on the operating system.
## Key Components of Docker
The following are the some of the key components of Docker:

#### Docker Engine:
It is a core part of docker, that handles the creation and management of containers.
#### Docker Image:
It is a read-only template that is used for creating containers, containing the application code and dependencies.
#### Docker Hub:
It is a cloud based repository that is used for finding and sharing the container images.
#### Dockerfile:
It is a script that containing instructions to build a docker image.
#### Docker Registry : 
It is a storage distribution system for docker images, where you can store the images in both public and private modes.
## Features of Docker
*Docker reduces the size of development by providing a smaller part of the OS via containers.

*It is easier to work on the same project by different teams with the help of Containers.

*Docker containers can be deployed anywhere, on any physical, or virtual machines and on the cloud.

*Docker containers are lightweight so, it becomes easy to scale them
## What is Docker Image?
It is a file, comprised of multiple layers, used to execute code in a Docker container. They are a set of instructions used to create docker containers. Docker Image is an executable package of software that includes everything needed to run an application. This image informs how a container should instantiate, determining which software components will run and how. Docker Container is a virtual environment that bundles application code with all the dependencies required to run the application. The application runs quickly and reliably from one computing environment to another.
## What is Docker Container?
Docker container is a runtime instance of an image. Allows developers to package applications with all parts needed such as libraries and other dependencies. Docker Containers are runtime instances of Docker images. Containers contain the whole kit required for an application, so the application can be run in an isolated way. For eg.- Suppose there is an image of Ubuntu OS with NGINX SERVER when this image is run with the docker run command, then a container will be created and NGINX SERVER will be running on Ubuntu OS.
## Docker Commands
Through introducing the essential docker commands, docker became a powerful software in streamlining the container management process. It helps in ensuring a seamless development and deployment workflows. The following are the some of docker commands that are used commonly:

### Docker Run:
It used for launching the containers from images, with specifying the runtime options and commands.
### Docker Pull:
It fetches the container images from the container registry like Docker Hub to the local machine.
### Docker ps :
It helps in displaying the running containers along with their important information like container ID, image used and status.
### Docker Stop :
It helps in halting the running containers gracefully shutting down the processes within them.
### Docker Start:
It helps in restarting the stopped containers, resuming their operations from the previous state.
### Docker Login:
It helps to login in to the docker registry enabling the access to private repositories.

## HOW TO INSTALL DOCKER
To install Docker on a remote server using PuTTY, you'll first need to ensure you have access to a Linux server (like Ubuntu, CentOS, etc.) via SSH. Here's a step-by-step guide:
#### Step 1: Connect to Your Server
Open PuTTY.
Enter the hostname or IP address of your server.
Click "Open" to initiate the connection.
Log in with your username and password.
#### Step 2: Update Your Package Index
sudo apt update
#### Step 3: Install Prerequisites
sudo apt install apt-transport-https ca-certificates curl software-properties-common
#### Step 4: Add Docker’s Official GPG Key
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
#### Step 5: Set Up the Stable Repository
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
#### Step 6: Install Docker
sudo apt update
sudo apt install docker-ce
#### Step 7: Verify Docker Installation To verify that Docker is installed correctly, run the following command:
docker --version
####Type the instance's IP and see Nginx default web page.# DOCKER
