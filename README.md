
# Spring Boot Projects

This repository contains two Spring Boot applications, each demonstrating different setups and integrations for development and testing environments.

## Projects Overview

### 1. Spring Boot Docker Compose

This project demonstrates how to set up a Spring Boot application with Docker Compose, featuring MariaDB, Redis, and NGINX for frontend integration. It also highlights the use of Devcontainers for an optimal development environment.

- **Location**: `spring-boot-docker-compose`
- **Medium Article**: [Under Pressure: Spring Boot and Docker Compose](https://medium.com/code-and-coffee/under-pressure-spring-boot-and-docker-compose-6573295b9e3a)

#### Prerequisites

- **IntelliJ Ultimate**: This repository is best opened with IntelliJ Ultimate for optimal configuration and support.

#### How to Run

1. Open the project in IntelliJ Ultimate.
2. Use the **"TeamaApplication"** run configuration to start the Docker Compose environment.
3. A sample page can be displayed via [http://127.0.0.1:8080/](http://127.0.0.1:8080/).

### 2. Spring Boot Testcontainers

This project demonstrates how to set up a Spring Boot application with Testcontainers for robust integration testing. It features MariaDB and Redis containers managed by Testcontainers.

- **Location**: `spring-boot-testcontainer`
- **Medium Article**: [Build Me Up Buttercup: Spring Boot and Testcontainers](https://medium.com/code-and-coffee/build-me-up-buttercup-spring-boot-and-testcontainers-84e4ab555eb7)

#### Prerequisites

- **IntelliJ Ultimate**: This repository is best opened with IntelliJ Ultimate for optimal configuration and support.

#### How to Run Tests

1. Open the project in IntelliJ Ultimate.
2. Use the persisted run configuration **"Run all tests"** to execute all tests with Testcontainers.

## Environment Variables

Both projects contain a `.env.template` that can be copied and modified to create your own `.env` file with the necessary environment variables.


---

For more details, please refer to the respective Medium articles linked above.

