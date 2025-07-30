# Dockerized-Apache-Web-Server-with-Docker-Hub-Integration
Ideal for DevOps beginners learning containerization, image building, and registry integration.  Features:  Dockerfile for Apache setup  Apache server running in a Docker container  Docker image built and tagged  Docker image pushed to Docker Hub.
First you should have to create a Docker file then you have to apply these commands.
" Commands "
docker build -t myapacheserver .
docker images
docker run –d –p 80:80 myapacheserver
browse localhost
