# Factorial
A payment processing service

####Skills & Tools Required
* Java 11
* Spring Boot 2.5.6
* Docker
* Apache Kafka
* Knowledge of Microservices

####Project Overview
* This project contains two microservices(User & Transaction service)
* Microservices have been registered in service registry using Eureka Server
* All configuration files for various microservices have been loaded from config-server which is also another microservice.
* Each microservice is a consumer as well producer of Kafka topics.
* Each project is build as separate docker image.
