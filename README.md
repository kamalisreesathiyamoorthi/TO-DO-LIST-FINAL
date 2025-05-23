# farm-stack-todo

This is a full-stack To-Do List app built using FastAPI for the backend and React for the frontend. The project includes:

- CRUD operations for to-do lists and tasks
- Schema validation
- Simple frontend UI built with React

It covers all the essential tools to build, run, and deploy a functional to-do list application.

## Tools Used

- **FastAPI** — Backend web framework for building APIs
- **React** — Frontend library for building UI
- **MongoDB Atlas** — Cloud-hosted NoSQL database to store user and task data
- **Motor** — Async MongoDB driver for Python
- **Axios** — HTTP client for frontend API requests
- **Docker & Docker Compose** — Containerizing frontend, backend, and database
- **NGINX** — Reverse proxy setup to route frontend and backend
- **Uvicorn** — ASGI server to run FastAPI app

## Tech Stack

- Python
- JavaScript (React)
- MongoDB (NoSQL)

## How to Run Locally

### Prerequisites

- Docker and Docker Compose installed
- MongoDB Atlas account set up with a cluster and connection URI ready

### Steps

1. Clone the repo:

   ```bash
   git clone https://github.com/kamalisreesathiyamoorthi/TO-DO-LIST-FINAL.git
   cd TO-DO-LIST-FINAL

2.Configure environment variables:

Create a .env file (or update your Docker environment variables) with your MongoDB Atlas URI, for example:

MONGODB_URI="mongodb+srv://username:password@cluster0.is1woh5.mongodb.net/database_name?retryWrites=true&w=majority&tls=true&appName=Cluster0"

3.Start the app using Docker Compose: docker-compose up --build

4.Access the frontend: http://localhost:3000

5.API documentation:http://localhost:3001/docs

6.Cleanup:
To remove project containers, volumes, and orphaned containers: docker-compose down --volumes --remove-orphans

