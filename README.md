# Crypto Tracker

## Overview
**Crypto Tracker** is a cryptocurrency transaction monitoring and fraud detection project. This project aims to track cryptocurrency wallet transactions, analyze patterns, and flag potentially fraudulent activity. Users can input a wallet address to trace its transaction movements, count usages, and visualize the total amount transferred or received. 

The project leverages **AWS**, **Airflow**, **Python**, **MongoDB**, **Docker**, and **GitHub Actions** for CI/CD, making it an end-to-end data engineering pipeline. Crypto Tracker is built with a focus on data engineering best practices, API integration, data pipeline automation, and real-time monitoring.

## Key Features
- **Transaction Tracking**: Allows users to input a wallet address and trace its entire transaction history.
- **Fraud Detection**: Utilizes network analysis and pattern recognition to identify suspicious behavior.
- **Real-Time Dashboard**: A live dashboard provides real-time transaction updates, usage counts, and visualized patterns.
- **Data Engineering Pipeline**: Built with Apache Airflow for scheduling and Docker for containerized deployment.
- **Deployment-Ready**: Hosted on AWS with CI/CD integration for rapid iteration and deployment.

## Tech Stack
- **Languages**: Python (Pandas, NetworkX for network analysis, Matplotlib/Plotly for visualization)
- **APIs**: CryptoCompare API, Etherscan API, Chainalysis API
- **Data Pipeline**: Apache Airflow, Docker, AWS S3, AWS Lambda
- **Database**: MongoDB (for transaction data storage) and PostgreSQL (for structured query data)
- **Visualization**: Streamlit and Dash for dashboard creation
- **Deployment and CI/CD**: GitHub Actions, AWS EC2, and CloudWatch for monitoring

## Repository Structure
```plaintext
crypto-tracker/
├── data-pipeline/         # Ingestion, processing, and transformation scripts
├── api/                   # API integration for cryptocurrency data
├── fraud_detection/       # Algorithms for fraud detection
├── dashboard/             # Code for dashboard app (Streamlit/Dash)
├── docker/                # Docker configuration files for each component
└── README.md              # Project overview and documentation
