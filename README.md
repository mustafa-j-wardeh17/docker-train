# Docker Training Projects

This repository contains various training projects to demonstrate how to containerize applications using Docker. Each project showcases different Docker setups and configurations, ranging from basic Dockerfile usage to more advanced multi-service setups with `docker-compose`.

## Project List

1. **hello-docker**
   - A simple introductory project using only a `Dockerfile` to build and run a basic application.

2. **react-docker**
   - A React.js project that uses a `Dockerfile` and `.dockerignore` to create a containerized development environment for React.

3. **vite-project-compose**
   - A Vite.js project using `Dockerfile`, `.dockerignore`, and `docker-compose.yaml` for setting up a development environment with Docker Compose.

4. **mern-docker**
   - A full-stack MERN (MongoDB, Express, React, Node.js) application, split into three services: web (React frontend), api (Express backend), and db (MongoDB database). Docker setup includes separate `Dockerfile`s for the frontend and backend, `.dockerignore`, and `docker-compose.yml` for orchestrating services.

5. **next-docker**
   - A Next.js application utilizing a `Dockerfile`, `.dockerignore`, and `docker-compose.yaml` to create a multi-service Docker environment for development.

Each project folder contains its own Docker configurations and instructions for setup.
