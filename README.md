# Log Monitor System with Kafka, PySpark, and Grafana

This project implements a real-time log monitoring pipeline using Apache Kafka, PySpark, PostgreSQL, Redis, and Grafana. It is designed to simulate application logs, process them in real time, store relevant metrics, and visualize system health using dynamic dashboards.

## Features

- Real-time log ingestion using Apache Kafka
- ETL processing and anomaly detection with PySpark
- Log persistence and querying through PostgreSQL
- In-memory analytics cache using Redis
- Pre-built Grafana dashboards for monitoring and visualization
- Docker Compose setup for running the full pipeline locally

## Architecture Overview

1. Log Producer: Emits JSON-formatted logs to Kafka topics
2. Kafka Broker: Receives and queues incoming log events
3. PySpark Job: Processes, filters, and transforms logs from Kafka
4. PostgreSQL: Stores processed logs for historical analysis
5. Redis: Caches real-time metrics and aggregations
6. Grafana: Visualizes alerts, trends, and system KPIs

## Tech Stack

- Apache Kafka
- Apache Spark (PySpark)
- PostgreSQL
- Redis
- Grafana
- Docker Compose
- Python

## Folder Structure





## Setup Instructions

1. **Start the full pipeline:**

```bash
docker-compose up --build
spark-submit spark/spark_job.py
Access Grafana Dashboard:

URL: http://localhost:3000

Default login: admin / admin

## Use Cases
Infrastructure log monitoring

Real-time system alerting and trend detection

Cloud-native observability pipelines

Author
Praveen Kumar Thabjul
