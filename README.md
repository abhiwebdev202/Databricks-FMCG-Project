# Databricks-FMCG-Project
A production-style data engineering project that demonstrates the implementation of a Lakehouse Architecture using Databricks, PySpark, SQL, and Delta Lake. The project follows the Medallion Architecture (Bronze → Silver → Gold) to transform raw data into analytics-ready datasets while ensuring scalability, reliability, and performance.

---

## Project Overview

This project simulates a modern enterprise data platform where raw data is ingested, cleaned, transformed, and curated into business-ready datasets.

The pipeline is designed using Databricks notebooks and PySpark, with Delta Lake providing ACID transactions, schema enforcement, and efficient storage for reliable data processing.

---

## Architecture

```
            Raw Data
                │
                ▼
         Bronze Layer
      (Raw Data Ingestion)
                │
                ▼
         Silver Layer
 (Data Cleaning & Transformation)
                │
                ▼
          Gold Layer
 (Business Ready Analytics)
```

### Bronze Layer
- Ingest raw datasets into Delta Lake
- Preserve original data without modifications
- Enable reproducibility and auditing

### Silver Layer
- Clean and validate data
- Handle missing and duplicate records
- Standardize data types
- Apply business transformation logic

### Gold Layer
- Create analytics-ready datasets
- Build aggregated and reporting tables
- Optimize datasets for downstream BI and reporting

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Databricks | Data engineering platform |
| PySpark | Distributed data processing |
| SQL | Data transformation and querying |
| Delta Lake | Reliable storage with ACID transactions |
| Python | Data processing logic |

---

## Project Structure

```
Databricks-Lakehouse-Engineering/
│
├── notebooks/
│   ├── bronze_ingestion.py
│   ├── silver_transformation.py
│   └── gold_aggregation.py
│
├── data/
│   ├── raw/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── sql/
│   └── analytics_queries.sql
│
├── images/
│   └── architecture.png
│
├── README.md
└── requirements.txt
```

---

## Features

- Medallion Architecture implementation
- Distributed ETL pipelines using PySpark
- Delta Lake storage format
- Data validation and cleansing
- Incremental transformations
- Scalable Spark processing
- SQL-based analytics layer
- Modular notebook organization

---

## Data Pipeline

1. Load raw data into the Bronze layer
2. Clean and validate records in the Silver layer
3. Transform datasets using PySpark
4. Store processed data in Delta Lake
5. Generate Gold datasets for analytics
6. Query curated data using SQL

---

## Skills Demonstrated

- Data Engineering
- Big Data Processing
- Lakehouse Architecture
- Medallion Architecture
- ETL Pipeline Development
- Distributed Computing
- Data Transformation
- Data Modeling
- Delta Lake
- Performance Optimization

---

##  Learning Outcomes

Through this project, I gained hands-on experience in:

- Designing scalable data pipelines
- Building Medallion Architecture using Databricks
- Processing large datasets with PySpark
- Implementing Delta Lake best practices
- Optimizing Spark transformations
- Creating analytics-ready datasets

---

## Future Improvements

- Implement Structured Streaming
- Add Delta Live Tables (DLT)
- Introduce Unity Catalog
- Integrate workflow orchestration
- Add automated testing
- Configure CI/CD pipeline
- Monitor pipelines with Databricks Jobs

---

## Author

**Abhinab Kashyap**

MSc Data Science | Aspiring Data Engineer

**Tech Stack**

`Databricks` • `PySpark` • `SQL` • `Python` • `Delta Lake` • `Data Engineering`

---

****If you found this project interesting, feel free to star the repository.
