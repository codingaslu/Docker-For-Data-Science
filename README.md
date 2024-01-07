# Docker-For-Data-Science

# Docker Commands README

This README provides a summary of Docker commands used in a Windows environment for managing Docker images and containers.

## Commands

Use these commands to manage Docker images and containers:

```bash
# Login to Docker Hub
docker login

# List Images
docker images

# Build an Image
docker build -t username/welcome-app .

# Alternative Build Command
docker build -t welcome-app .

# Push an Image to Docker Hub
docker push username/welcome-app:latest

# Pull an Image from Docker Hub
docker pull username/welcome-app:latest

# Run a Container from an Image
docker run -d -p 5000:5000 username/welcome-app:latest

# Run Container Mapping Port 500:5000
docker run -p 500:5000 welcome-app

# Show Running Containers
docker ps

# Stop a Running Container
docker stop CONTAINER_ID
