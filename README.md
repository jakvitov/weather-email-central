# Weather-email central repository
A central repository for Weather email project, that holds compose files and deployment configurations for the whole project as well as documentation.

## Microservice repositories

- [Weather api consumer](https://github.com/jakvitov/weather-api-consumer)

- [Weather email producer](https://github.com/jakvitov/weather-email-producer)

- [Weather dto](https://github.com/jakvitov/weather-dto)

- [Weather user administration](https://github.com/jakvitov/weather-user-administration)


## Architecture
The whole project is build using a microservice, not because it was suitable for this project, but rather because I wanted to try out designing a whole applictaion from the very beginning myself, using this pattern. 

## Microservice diagram
![Application architecture diagram](https://github.com/jakvitov/weather-email-central/blob/main/diagrams/Weather-email-microservice-diagram.png)

## Deployment
- This project is made as a personal one and is deployed only for my personal use on free tier Oracle cloud. Because of that, the application is deployed only using Docker compose and not Kubernetes. 
- Docker image can be created with given Dockerfile for any of the microservices.
- Then the compose.yaml is used to compose the container.
- All environment vaiables need to be specified in ./env/env-variables.env

## Todo list
[Todo list](https://github.com/users/jakvitov/projects/2/views/1)

