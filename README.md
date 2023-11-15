# Containerized React-Node Application

This repository contains a Dockerized multi-container application with a React front end and a Node.js back end. Use Docker Compose to easily set up and run the entire application stack.

## Prerequisites

Make sure you have Docker and Docker Compose installed on your machine. If not, you can download and install them from [Docker's official website](https://www.docker.com/get-started).

## Running the Application

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
Build the Docker images:

bash
Copy code
docker-compose build
Start the application:

bash
Copy code
docker-compose up
This command will start the React front end and Node.js back end services. The application will be accessible at http://localhost:3000.

To stop the application, press Ctrl + C in the terminal where the docker-compose up command is running.
