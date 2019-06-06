# ci-project-kube
## Description
This project will explore to set up a continuous integration pipeline for an application that provides a login system consisting of 
14 components. This will be achieved using kubernetes, jenkins and docker-compose. The architecture diagram below displays the 
connections between the 14 services. (Note: this project builds on a previous project https://github.com/Sajith75/ci-project)

## Architecture Diagram
![architecture diagram](ci-project-diagram.png)

## Prerequisites
The images of the microservices required for this project can be accessed from docker hub:
* sajith75/mongo-service
* sajith75/aes-encryption-service
* sajith75/email-service
* sajith75/secret-service
* sajith75/account-service
* sajith75/session-token-service
* sajith75/dashboard-service
* sajith75/authentication-service
* sajith75/deashboard-client
* sajith75/authentication-client
* sajith75/gateway
* sajith75/role-service
* sajith75/group-service
