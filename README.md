# Docker-Container-Management

## Introduction
The Docker API has allowed limitless options for interfacing with Docker engine, containers, and images to emerge from CLIs to desktop applications and web-based management tools.

Everything the Docker client can do can be done with the API.

Below GUI tools extensively uses API to interface with Docker engine.

## Requirement
Create a web application tool for managing Docker environments

## Solution
Use <b>Portainer</b>(formerly UI for Docker) is a free open-source web application that runs as a container itself.

Portainer makes wide use of the Docker API to handle its interactions and monitoring, but for automation, also exposes its own API and template file format. 

Portainer covers most major areas of Docker you would want to interact with, offering creation, editing, management, monitoring and deletion of containers, as well as the ability to add, remove, and view images, networks, and volumes, but not edit them.

## Installation

```
docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer
```

## Demo

<img src="https://d1jiktx90t87hr.cloudfront.net/354/wp-content/uploads/sites/2/2018/12/Containers1.png" ></img>
