# pineapple Application

## Description

This application was developed during the winter semester 21/22 in component based development.

## Features

Inside this repository you will find all the repositories this project is made of.

## Clone this repository including the submodules

To clone the repository via the command line please proceed as follows:
```
git clone git@github.com:QRG-low/pineapple.git --recurse-submodules 
```
for SSH
and 
```
git clone https://github.com/QRG-low/pineapple.git --recurse-submodules
```
for HTTPS

then for each submodule
```
./mvnw spring-boot:run
```

## Authors

- Hitzek, Steffen; Matr.Nr 566507 
- Schöbel, Susann; Matr.Nr 571657

## Used Technologies

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Maven](https://maven.apache.org/)
- [Swagger](https://swagger.io/)

## Project

In the course of the KBE module in winter semester 21/22, the "pineapple project" was created. It consists of various microservices and represents a web shop.

The full project includes:
- ["Mehrwertsteuer" Calculator microservice](https://github.com/QRG-low/pineapple_calculator)
- [Storage microservice](https://github.com/QRG-low/pineapple_storage)
- [Application microservice](https://github.com/QRG-low/pineapple_service)
- [Gateway](https://github.com/QRG-low/pineapple_gateway)
- [Frontend](https://github.com/QRG-low/pineapple_frontend)