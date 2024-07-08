# Full Stack Web Application Deployment

This repository contains the Docker configuration files for deploying a full stack web application, which includes a React frontend and a FastAPI backend.

## Prerequisites

- Docker installed
- Docker Compose installed
- npm installed
- git installed
- python installed

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

## Deploy using Docker locally

```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Frontend

cd frontend

docker build -t frontend-image .

docker run -d -p 5173:5173 frontend-image

# Backend

cd backend

docker build -t backend-image .

docker run -d -p 8000:8000 backend-image
