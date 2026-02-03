# FAANG Stock Data Analytics  

A **distributed data analytics project** that analyzes historical FAANG stock prices using **PySpark on Apache Spark**, backed by **Hadoop (HDFS/YARN)** and deployed via **Docker**.

---

## Overview

This project explores historical stock price data for **Amazon, Apple, Facebook (Meta), Google, and Netflix** in a **big-data environment**.  
All analysis is performed using **PySpark DataFrames**, enabling scalable processing and comparison across multiple companies.

---

## What I Analyzed

Using **PySpark**, the project includes:

- Data ingestion and cleaning with Spark DataFrames  
- Time-series analysis of stock price trends  
- Comparison of price movement and volatility across FAANG stocks  
- Aggregations and statistical summaries (e.g. averages, returns, ranges)  
- Distributed computation executed on a Spark cluster  

Analysis is conducted interactively in a **Spark-enabled Jupyter Notebook**.

---

## Tech Stack

- **PySpark** (primary analysis engine)  
- Apache Spark  
- Hadoop (HDFS, YARN)  
- Docker & Docker Compose  
- Jupyter Notebook  
- Python  

---
## How to Run

```bash
docker-compose up -d
```

---

### Access

- Jupyter Notebook: http://localhost:8888
- Spark UI: http://localhost:8080
- Hadoop NameNode UI: http://localhost:80

---

### Key Highlights

- End-to-end PySpark data analysis
- Production-style Spark + Hadoop setup
- Distributed processing on a multi-node cluster
- Fully reproducible Docker-based environment
