# SampleDotNetCore Application

Project for web Api monitoring

The purpose of this project is to create a monitoring dashboard on web api.

We will use :

## Presentation

## Dockerfile 


docker build --pull -t sampledotnetcoreapp .
docker run --name sampledotnetcoreapp --rm -it -p 8000:80 sampledotnetcoreapp

ping http://localhost:8000/api/values