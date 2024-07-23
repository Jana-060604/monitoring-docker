# Monitoring Docker Containers with Prometheus and Grafana

This repository contains a Docker Compose setup to monitor Docker containers using Prometheus and Grafana.

## Setup Instructions

1. **Clone the Repository**:
    ```sh
    git clone <your-repo-url>
    cd monitoring-docker
    ```

2. **Run Docker Compose**:
    ```sh
    docker-compose up -d
    ```

3. **Access Grafana**:
    Open your browser and go to `http://localhost:3000`. Login with `admin/admin` and configure your dashboards.

## Configuration Files

- `prometheus.yml`: Configuration for Prometheus.
- `datasource.yml`: Configuration for Grafana to use Prometheus as a data source.
- `docker-compose.yml`: Docker Compose file to set up Prometheus, Grafana, and Node Exporter.
