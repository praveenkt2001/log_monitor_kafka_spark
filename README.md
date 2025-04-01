# Real-Time Log Monitoring System 📊🚀

A Kafka + PySpark-powered pipeline that ingests app logs and streams insights into PostgreSQL with real-time dashboards via Grafana.

## Features
- Kafka-based event ingestion
- PySpark ETL and anomaly detection
- PostgreSQL data store
- Grafana dashboards for visualization
- Redis for real-time KPI cache

## Setup
1. Start Kafka + Spark: `docker-compose up`
2. Run Spark Job: `spark-submit spark_job.py`
3. Open Grafana at `localhost:3000`