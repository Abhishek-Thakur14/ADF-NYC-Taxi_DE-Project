ADF-NYC-Taxi_DE-Project 🚖 | Real-Time Data Pipeline on Azure

I'm excited to present my ADF-NYC-Taxi_DE-Project, a comprehensive Data Engineering project built on Microsoft Azure that implements a real-time data pipeline to ingest, process, and analyze NYC Taxi trip data from a live Web API. This project is designed to handle large-scale data efficiently using Medallion Architecture and Unity Catalog for better data governance and security.
🔍 Project Overview:

The project aims to build a dynamic data pipeline that extracts NYC Taxi trip data from a public API, stores it in Azure Data Lake, processes the data using Azure Databricks & PySpark, and organizes it into Bronze, Silver, and Gold layers using Delta Lake. The entire pipeline is automated through Azure Data Factory (ADF), ensuring real-time data processing and scalability.
🏗 Architecture Flow:

    Data Ingestion (Bronze Layer):
        Azure Data Factory pipelines fetch real-time data from the NYC Taxi API using REST API calls.
        The data is stored in Azure Data Lake Storage (ADLS) in its raw format (Bronze layer).
        Dynamic linked services and datasets are created to automate the pipeline.

    Data Cleaning & Transformation (Silver Layer):
        Azure Databricks with PySpark processes raw data by cleansing, filtering, and applying transformations.
        Data quality checks like handling null values and date conversions are performed.
        The clean data is stored in Delta Tables with schema enforcement.

    Data Aggregation & Analytics (Gold Layer):
        Aggregated trip statistics such as fare analysis, trip duration, and popular routes are generated.
        Optimized data is stored in Delta Lake for business intelligence and reporting.

🔑 Key Features:
Feature	Description
Data Ingestion	Real-time data extraction using Azure Data Factory
Transformation	Data cleansing, aggregation, and feature engineering with PySpark
Data Storage	Delta Lake with ACID Transactions and Schema Evolution
Data Versioning	Implemented Time Travel for data recovery
Security & Governance	Managed access with Unity Catalog
Automation	ADF dynamic pipelines with parameterized datasets
🛠 Tech Stack Used:

    Azure Data Factory (ETL Pipelines)
    Azure Data Lake Storage
    Azure Databricks
    Unity Catalog
    PySpark
    Delta Lake
    REST API

Outcome & Learnings:

This project was a fantastic learning experience in building real-time data pipelines on Azure. It helped me gain hands-on knowledge in Big Data processing, Cloud Data Engineering, and Data Governance. Implementing the Medallion Architecture along with Delta Lake improved data reliability, while Unity Catalog ensured seamless data management and security.
Looking Forward:

I'm eager to explore more cloud-based data engineering solutions, including streaming data pipelines, serverless architectures, and machine learning integrations.

Let's connect and discuss more about Data Engineering, Cloud Solutions, and Real-Time Data Processing! 🚀
