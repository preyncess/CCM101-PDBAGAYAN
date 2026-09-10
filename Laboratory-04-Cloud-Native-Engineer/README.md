# Laboratory 04 – Cloud-Native Engineer

## Mission Overview

This laboratory activity helped me understand the basic concepts of cloud-native engineering and containerization. I learned how Virtual Machines differ from Containers and gained hands-on experience using Docker to deploy an Nginx web server. I completed the activities using the KillerCoda Docker playground.

## Objectives

- Learn the main differences between Virtual Machines and Containers.
- Check if Docker is properly installed and running.
- Practice using basic Docker CLI commands.
- Download and run an Nginx container.
- Understand how host and container ports are connected.
- Practice managing the different stages of a Docker container.
- Record and organize Docker procedures using Markdown.

## Docker Commands Executed

### Check Docker Installation

```bash
docker --version
```

### Check Docker Information

```bash
docker info
```

### Pull Nginx

```bash
docker pull nginx
```

### Run Nginx

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

### List Running Containers

```bash
docker ps
```

### Test Nginx

```bash
curl http://localhost:8080
```

### Stop Container

```bash
docker stop nginx-server
```

### View All Containers

```bash
docker ps -a
```

### Remove Container

```bash
docker rm nginx-server
```

## Skills Learned

- Basic Docker CLI usage
- Deploying containers
- Setting up an Nginx web server
- Understanding port mapping
- Managing the Docker container lifecycle
- Using Linux terminal commands
- Creating technical documentation in Markdown
- Organizing projects in GitHub

## Challenges Encountered

One challenge I experienced was understanding the difference between Virtual Machines and Docker containers. I also had to learn how port mapping allows me to access a web server running inside a container. By practicing the Docker commands, I was able to understand the process more clearly. I also needed to carefully check the container status to make sure the Nginx container was successfully stopped and removed.
