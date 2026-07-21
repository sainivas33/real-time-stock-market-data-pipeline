# Real-Time Stock Market Data Pipeline

## Overview

This project demonstrates a real-time data engineering pipeline built using Apache Kafka and AWS cloud services.

The pipeline collects stock market data, streams it through Kafka, stores it in Amazon S3, and enables analytics through AWS Glue and Athena

## Architecture 
<img src="Architecture.jpg">

## Architecture

Stock Market Data
        ↓
Kafka Producer
        ↓
Kafka Topic
        ↓
Kafka Consumer
        ↓
Amazon S3
        ↓
AWS Glue
        ↓
AWS Athena

## Technologies Used

- Python
- Apache Kafka
- AWS EC2
- AWS S3
- AWS Glue
- AWS Athena

## Features

- Real-time stock market data ingestion
- Event-driven data streaming
- Cloud-based storage architecture
- Querying and analytics using Athena
- Scalable data pipeline design

## Future Enhancements

- Docker
- Apache Spark
- Apache Airflow
- Real-time dashboards

## Author

Sainivas Katika
