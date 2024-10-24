# CrimsonSky - Api Gateway Microservice

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=bugs)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)

## Live Link / Demo Link: 🔗
Access the flight service at **[localhost:8765](http://localhost:8765)**

## Table of Contents: 📑

- [About The Service](#about-the-service-)
- [Technologies](#technologies-%EF%B8%8F)
- [Setup](#setup-)
- [Approach](#approach-)
- [Status](#status-)
- [License](#license-%EF%B8%8F)

## About the Service: 📚
The **Api Gateway Service** is a starting point of the CrimsonSky flight booking system. It manages the api requests to the application. The service is built with **Spring Boot** and uses **Spring Cloud Gateway** for routing, **Spring Cloud Netflix Eureka** for service discovery and **Spring Security** for security, ensuring secure and efficient microservice communication.

## Technologies: ☕️

- Java
- Spring Boot
- Spring Cloud Gateway
- Spring Cloud Netflix Eureka
- Swagger OpenAPI

## Setup: 💻

- **Install Java 21 :**
    - Download and install **[Java 21](https://www.oracle.com/in/java/technologies/downloads/#java21)**
    - Set up the **JAVA_HOME** environment variable.


- **Install Maven:**
    - Download and install **[Maven](https://maven.apache.org/download.cgi)**
    - Add the **bin** directory to the **PATH** environment variable.

**Available Scripts:**

In the project directory, you can run:

- #### `mvn install`
  Installs all necessary dependencies.

- #### `mvn spring-boot:run`
  Runs the api-gateway service.\
  Open [http://localhost:8765](http://localhost:8765) to access it.

# Approach: 🚶
This service is part of the **CrimsonSky** microservices ecosystem, focusing on user autentication and microservices communication using **Netflix Eureka** and **Spring Security**  for optimal performance and security.

# Status: 📶
Service under development 🛠️

# License: ©️
MIT License (**[Check Here](LICENSE)**)