# AeroGuard: Industrial Predictive Maintenance Pipeline

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Ready-blue)
![Status](https://img.shields.io/badge/Status-Active_Development-green)

## Project Overview
This project implements a scalable **MLOps architecture** to predict the Remaining Useful Life (RUL) of NASA CMAPSS jet engines. It simulates a real-world industrial IoT environment where sensor data is streamed, processed, and monitored in real-time.

## Tech Stack
- **Ingestion:** Apache Kafka
- **Model:** LSTM / XGBoost
- **Serving:** FastAPI & Docker
- **Orchestration:** Kubernetes (Minikube)
- **Monitoring:** Prometheus & Grafana