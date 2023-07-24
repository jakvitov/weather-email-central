# Weather-email central repository
A central repository for Weather email project, that holds compose files and deployment configurations for the whole project as well as documentation.

## Architecture
The whole project is build using a microservice, not because it was suitable for this project, but rather because I wanted to try out designing a whole applictaion from the very beginning myself, using this pattern. 

## Microservice diagram
![Application architecture diagram](../weather-email-central/diagrams/Weather-email-microservice-diagram.jpeg)

## Deployment
- This project is made as a personal one and is deployed only for my personal use on free tier Oracle cloud. Because of that, the application is deployed only using Docker compose and not Kubernetes. 
- For testing purposes, some microservices have local deployment *.bat* script to build and run them as individual Docker container on port 8080.
- When deploying the container using the deployment *.bat* file, you need to set all the necessary *env* variables on your system. (such as api keys etc.)

## Todo list
[Todo list](https://github.com/users/jakvitov/projects/2/views/1)
