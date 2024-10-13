# Flask Docker Demo

This is a demo project for a Flask application running in Docker. It serves as a template for creating and deploying Flask applications using Docker and Docker Compose.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Building and Running the Application](#building-and-running-the-application)

## Features

- Simple Flask application with RESTful API endpoints
- Dockerized application for easy deployment
- Docker Compose for managing multi-container applications

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

To get a local copy up and running, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/Hossam-Shehadeh/flask_docker_demo
cd flask_docker_demo
```

### 2. Build and run the application using Docker Compose

```bash
docker-compose up --build
```

### 3. Open your browser

Go to http://localhost:5000 to see the application in action.

Building and Running the Application

To build and run the application in detached mode, use:
```bash
docker-compose up --build -d
```

To stop the application, run:
```bash
docker-compose down
```
