# Enterprise Retail Data Lake & Analytics Platform

## Project Overview

This project focuses on building an end-to-end cloud-based data lake and analytics platform using Amazon Web Services (AWS).

The goal is to ingest, store, clean, transform and analyse retail transaction data using AWS cloud services and Python-based data engineering technologies.

The project follows a Bronze, Silver and Gold data architecture to organise data at different stages of processing.

## Business Problem

Retail businesses generate large volumes of transactional data. Without proper data processing and organisation, it becomes difficult to maintain data quality, analyse sales performance and generate meaningful business insights.

This project aims to build a scalable data pipeline that transforms raw retail transaction data into structured, analytics-ready datasets.

## Dataset

**Online Retail Dataset – UCI Machine Learning Repository**

- Approximately 541,909 transaction records.
- 8 original columns.
- Contains invoice details, products, quantities, prices, customer IDs and countries.

Dataset source: https://archive.ics.uci.edu/dataset/352/online+retail

## AWS Architecture

The planned architecture includes:

1. Amazon S3 – Raw data storage.
2. AWS Glue – ETL processing and transformation.
3. PySpark – Data cleaning and transformation.
4. Amazon S3 – Processed and curated data storage.
5. AWS Glue Data Catalog – Metadata management.
6. Amazon Athena – SQL-based data analytics.

## Data Lake Architecture

### Bronze Layer – Raw Data
Stores the original source dataset in Amazon S3.

### Silver Layer – Processed Data
Cleans and transforms raw data, handles duplicates and missing values, and converts the output into Parquet format.

### Gold Layer – Curated Data
Will contain business-ready datasets for retail analytics and reporting.

## Technologies

- Amazon S3
- AWS Glue
- PySpark
- Python
- AWS Glue Data Catalog
- Amazon Athena
- Git and GitHub

## Project Status

**Currently in progress.**

Completed:
- Created AWS S3 bucket.
- Established Bronze, Silver and Gold folder structure.
- Downloaded the UCI Online Retail dataset.
- Uploaded original Excel and CSV datasets to the Bronze layer.
- Prepared the initial PySpark ETL script.

Upcoming:
- Configure and execute AWS Glue ETL job.
- Transform raw CSV data into Parquet.
- Create metadata tables using AWS Glue Data Catalog.
- Query processed data using Amazon Athena.
- Develop curated retail analytics datasets.

## Expected Business Outcomes

- Improved data quality.
- Structured retail transaction storage.
- Efficient data processing using cloud technologies.
- SQL-based retail analytics.
- Better understanding of end-to-end data engineering workflows.

---

*This project is being developed as a practical cloud data engineering portfolio project.*dme 
<img width="1672" height="941" alt="Enterprise Retail Data Lake Architecture" src="https://github.com/user-attachments/assets/080db9a9-a3a6-4162-86d7-79c65dcff267" />

