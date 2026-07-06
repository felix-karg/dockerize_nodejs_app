# Module 7.10 of DevOps Bootcamp by [TechWorld with Nana](https://www.techworld-with-nana.com/)
Dockerize Node.js application

## Technologies used:
- Docker
- Node.js

## Project Description:
- Write Dockerfile to build a Docker image for a Node.js application

## Implementation Steps:
1. Create Dockerfile (see `Dockerfile` in this repository)
2. Create image with `docker build -t my-app:1.0 .` (`-t` flag specifies image name and tag, `.` specifies location of the Dockerfile)
3. Verify that the new image is available with `docker images`
4. Start container with `docker run my-app:1.0`
5. View container logs with `docker logs <container-id>`
6. Login to container with `docker exec -it <container-id> /bin/sh`
