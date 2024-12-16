# FastAPI Application with PostgreSQL and Docker
## Project Description
This project demonstrates a basic FastAPI application integrated with PostgreSQL, using Docker for containerization. The application provides an API to interact with the database and follows modern web development practices.

## Features
RESTful API built with FastAPI.
PostgreSQL as the database backend.
Containerized setup using Docker Compose.
Interactive API documentation available at /docs.

![image](https://github.com/user-attachments/assets/4ace378d-aa0e-4818-96c3-1bb537ec9571)

## Requirements
Before you begin, ensure that you have the following installed:

Docker
Docker Compose

## Check the application:

Open http://localhost:8000.
View the API documentation at http://localhost:8000/docs.

# Troubleshooting
psycopg2 Installation Error:

## Replace psycopg2 with psycopg2-binary in requirements.txt.
Container Fails to Start:

Check the logs:
bash
Kopier kode
docker-compose logs
