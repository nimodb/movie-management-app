# Movie Manager App

This is a simple web application for adding and removing movies. It includes a React frontend, a Node.js backend, and a MongoDB database.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Clone the repository

```sh
git clone https://github.com/nimodb/movie-management-app.git
cd movie-manager-app
```

### Running the Application

To run the application, simply use the following command:
```sh
docker-compose up
```
This command will build and start all the services defined in the docker-compose.yml file.

### Accessing the Application
- Frontend: http://localhost:3000
- Backend API: http://localhost:3001
- MongoDB: localhost:27017 (you can connect using MongoDB clients)

### Stopping the Application

To stop the application and remove all running containers, use the following command:
```sh
docker-compose down
```