# Projectopdracht-Hess117 
Houssam El Gharbi

This repository contains the code for Projectopdracht-Hess117.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Docker](#docker)
- [Architectural Overview](#architectural-overview)


## Project Overview

This  repository is part of Projectopdracht for devops 2023/24. It handles the server-side logic and interacts with the database to support the project's functionality.

## Project Structure

The project is organized with the following key files and directories:
**backend/**
- `.dockerignore`
- `Dockerfile`
- `index.js`
- `package-lock.json`
- `package.json`
- `todo-inmemory.js`
- `todo-mysql.js`
- `verify.js`
- **frontend/**
  - `Dockerfile`
  - `index.html`
  - `jquery.min.js`
  - `nginx.conf`
  - `style.css`
- `architectuur.png`
- `docker-compose.yml`
- `init.sql`

## Getting Started

To run the containers locally, follow these steps:

1. Clone this repository.
2. docker compose up --build -d

## Docker

To build and run the application using Docker, use the provided Dockerfiles and docker-compose.yml files.


## Architectural Overview

Refer to the `architectuur.png` file for an architectural overview of the project.




