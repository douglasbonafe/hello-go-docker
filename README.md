# About
In this small project, I am creating a docker-compose to build a Hello World with Go Lang.
The challanges we are dealing with in this project are:

- create a deploy of a golang program in a personalized Dockerfile for production environment.
- execute the service and deatach the terminal.
- the final deploy image should be smaller than 2MB. So, we are implementing strategies like multistage build.
- we pushed the image in the dockerhub:
    https://hub.docker.com/repository/docker/dsbonafedev/hello-go/general