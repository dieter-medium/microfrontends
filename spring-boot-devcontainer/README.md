# Spring Boot Docker Compose with Devcontainers

This repository contains the source code for the Medium
article: [Back in Black: Spring Boot and Devcontainers](https://medium.com/code-and-coffee/back-in-black-spring-boot-and-devcontainers-411985db9831).

## Overview

This project demonstrates how to set up a Spring Boot application with Devcontainers, featuring MariaDB, Redis, and
NGINX for frontend integration. It also highlights the use of Testcontainers for robust integration testing.

## Prerequisites

- **IntelliJ Ultimate**: This repository is best opened with IntelliJ Ultimate for optimal configuration and support.

## Run Configuration

There is a run configuration named **"TeamaApplication"** which starts the Docker Compose environment outside of
Devcontainers.

## How to Run

1. Open the project in IntelliJ Ultimate.
2. Use the **"TeamaApplication"** run configuration to start the Docker Compose environment.
3. A sample page can be displayed via [http://127.0.0.1:8080/](http://127.0.0.1:8080/).

## Run as Devcontainer

1. Open the project in IntelliJ Ultimate.
2. Right-click on the [.devcontainer/devcontainer.json](.devcontainer%2Fdevcontainer.json) folder and select **"Dev
   Containers >" "Create Dev Containers and mount sources .."**.
3. Use the **"TeamaApplication DevContainer"** run configuration to start the app.

## Testing with Testcontainers within Devcontainers

You can run all tests using the persisted run configuration **"Run all tests in Devcontainer"**. This setup ensures that
all necessary
Testcontainers are started and managed correctly during the test execution.

## Components

- **MariaDB**: Database
- **Redis**: Data cache
- **NGINX**: Web server for frontend integration

## Environment Variables

The project contains a `.env.template` that can be copied and modified to create your own `.env` file with the necessary
environment variables.

---

For more details, please refer to
the [Medium article](https://medium.com/code-and-coffee/back-in-black-spring-boot-and-devcontainers-411985db9831).
