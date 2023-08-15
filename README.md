# Weather-email central repository
A central repository for Weather email project, that holds compose files and deployment configurations for the whole project as well as documentation.

## Microservice repositories

- [Weather email service (Java backend)](https://github.com/jakvitov/weather-email-service)

- [Weather graph generator - not yet made](#)

- [Weather email service UI (React frontend)](https://github.com/jakvitov/web-email-service-ui)


## Services diagram
![Application architecture diagram](https://github.com/jakvitov/weather-email-central/blob/main/diagrams/Weather-email-microservice-diagram.png)

## Deployment
- This project is made as a personal one and is deployed only for my personal use on my raspberry pi. Because of that, the application is deployed only using Docker compose and not Kubernetes. 
- All environment vaiables need to be specified in ./env/env-variables.env


