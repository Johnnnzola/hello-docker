# Hello Docker

 Docker project, built while learning containerization with Docker and Node.js.

## Overview

This project demonstrates how to package a simple Node.js application into a Docker container.

The project uses:

* Docker
* Node.js
* Ubuntu/Kali Linux environment
* Dockerfile
* Git and GitHub

## Project Structure

```text
hello-docker/
├── Dockerfile
├── app.js
└── README.md
```

## Dockerfile

The Dockerfile:

1. Uses the official Node.js Alpine image.
2. Creates `/app` as the working directory.
3. Copies the project files into the container.
4. Runs `app.js` with Node.js.

## Build the Image

Clone the repository and enter the project directory:

```bash
cd hello-docker
```

Build the Docker image:

```bash
docker build -t hello-docker .
```

## Run the Container

```bash
docker run --rm hello-docker
```

## Verify the Image

```bash
docker images
```

## Learning Objectives

This project is part of my hands-on learning in:

* Containerization
* Linux administration
* Docker
* DevOps and cloud technologies

## Author

John Nzola Musyoka

Cybersecurity Engineer | Ethical Hacker | ICT Professional
