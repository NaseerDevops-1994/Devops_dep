# Dockerized Node.js Application with Loki, Grafana, and Promtail

This project demonstrates how to Dockerize a Node.js application using best practices and set up logging with Loki, Grafana, and Promtail.

## Getting Started

### Prerequisites

- Docker installed on your machine: [Docker Installation Guide](https://docs.docker.com/get-docker/)
- Docker Compose installed on your machine: [Docker Compose Installation Guide](https://docs.docker.com/compose/install/)

### Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git

1. Navigate to the project directory:
cd your-repository

2. Create necessary configuration files:

Create a promtail-config.yml file in the ./promtail-config directory.
Create a loki-config-local.yaml file in the ./loki-config directory.

3. Build and start the Docker containers:
docker-compose up -d

This will start the Node.js application, Loki, Grafana, and Promtail.

4. Access Grafana at http://localhost:3000 (username: admin, password: admin) to set up dashboards and explore logs.