# Real-Time-Market-Sentiment-Price-Analytics-Pipeline
Real-Time Market Sentiment & Price Analytics Pipeline

A real-time data engineering and analytics pipeline that collects financial market data and social media sentiment, processes the text using NLP, and generates live sentiment scores for market analysis.

The system streams data using Apache Kafka, performs sentiment analysis using VADER NLP, and stores processed results in Azure for further analytics and visualization.

Project Overview

Financial markets are heavily influenced by public sentiment. This project builds a real-time pipeline that gathers financial and social media data, analyzes sentiment using natural language processing, and produces live analytics.

The pipeline demonstrates how modern data systems handle streaming ingestion, processing, and cloud storage using scalable technologies.

Architecture

Data Sources
Financial APIs + Social Media Text

Data Ingestion
Python scripts collect and publish data streams to Kafka topics.

Streaming Pipeline
Apache Kafka processes incoming data streams.

Data Processing
Python + Pandas clean and structure the incoming data.

Sentiment Analysis
VADER NLP calculates sentiment scores for each text record.

Storage Layer
Processed sentiment and market data are stored in Azure storage for future analysis.

Containerization
Docker is used to containerize the services for easy deployment.

Tech Stack

Python
Apache Kafka
Docker
Azure Cloud Storage
Pandas
REST APIs
VADER Sentiment Analysis (NLP)

Key Features

Real-time ingestion of financial and social media data
Kafka-based streaming data pipeline
Natural language sentiment analysis using VADER
Data cleaning and processing using Pandas
Cloud storage integration with Azure
Containerized deployment using Docker
