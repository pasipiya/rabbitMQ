# RabbitMQ with Docker Compose

This repository sets up RabbitMQ with Docker Compose using custom credentials (username and password) stored in an `.env` file. It also exposes the RabbitMQ management UI for easy access and monitoring.

## Prerequisites

- Docker and Docker Compose must be installed on your machine.

### Installing Docker and Docker Compose

1. Install Docker: [Install Docker](https://docs.docker.com/get-docker/)
2. Install Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Setup

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Run Composer

```bash
docker-compose up -d
docker-compose down
```

### 3. Access RabbitMQ Management UI

Once the container is running, you can access the RabbitMQ management UI at:

1. URL: <http://localhost:15672>
2. Username: myuser (replace with the value from your .env file)
3. Password: mypassword (replace with the value from your .env file)