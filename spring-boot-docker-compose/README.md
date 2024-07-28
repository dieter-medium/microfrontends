# Spring Boot Docker Compose

This repository contains the source code for the Medium
article: [Under Pressure: Spring Boot and Docker Compose](https://medium.com/code-and-coffee/under-pressure-spring-boot-and-docker-compose-6573295b9e3a).

## Overview

This project demonstrates how to set up a Spring Boot application with Docker Compose, featuring MariaDB, Redis, and
NGINX for frontend integration. It also highlights the use of Devcontainers for an optimal development environment.

## Prerequisites

- **IntelliJ Ultimate**: This repository is best opened with IntelliJ Ultimate for optimal configuration and support.

## Run Configuration

There is a run configuration named **"TeamaApplication"** which starts the Docker Compose environment.

## How to Run

1. Open the project in IntelliJ Ultimate.
2. Use the **"TeamaApplication"** run configuration to start the Docker Compose environment.
3. A sample page can be displayed via [http://127.0.0.1:8080/](http://127.0.0.1:8080/).

## Components

- **MariaDB**: Database
- **Redis**: Data cache
- **NGINX**: Web server for frontend integration

## Environment Variables

The project contains a `.env.template` that can be copied and modified to create your own `.env` file with the necessary
environment variables.

---

For more details, please refer to
the [Medium article](https://medium.com/code-and-coffee/under-pressure-spring-boot-and-docker-compose-6573295b9e3a).
