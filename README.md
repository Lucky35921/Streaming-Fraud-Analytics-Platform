
# Streaming Fraud Analytics Platform

### Apache Kafka | Spark Structured Streaming | AWS S3 | Redshift

## Project Architecture

![Streaming Fraud Architecture](streaming-fraud-analytics-platform/docs/architecture.svg)

## Project Overview

A real-time fraud analytics platform designed to process financial transactions, detect suspicious activities, and generate fraud alerts using an event-driven data engineering architecture.

The project focuses on scalable streaming, transaction validation, anomaly detection, and reliable data processing.

## Technology Stack

- **Programming:** Python, SQL, PySpark
- **Streaming:** Apache Kafka, Spark Structured Streaming
- **Cloud:** AWS S3, Amazon Redshift
- **Monitoring:** Amazon CloudWatch
- **Architecture:** Event-Driven Data Processing

## Key Features

- Transaction event ingestion
- Duplicate transaction detection
- High-value transaction identification
- Transaction velocity analysis
- Rule-based fraud detection
- Fraud alert generation
- Data validation and error handling

## Data Pipeline

Transaction Producers → Kafka → Spark Structured Streaming → Fraud Detection → AWS S3 → Redshift → Analytics

## Project Status

**In Development**

The local Python fraud detection prototype is available. Kafka, Spark Streaming, and AWS integrations are planned.

## Future Enhancements

- Kafka-based real-time ingestion
- Spark windowing and watermarking
- AWS S3 and Redshift integration
- Automated monitoring and alerting
- CI/CD deployment

## Author

**Lakshmana Rao Vallapuneni**

[LinkedIn](https://www.linkedin.com/in/lakshmanarao-vallapuneni/) | [GitHub](https://github.com/Lucky35921)
