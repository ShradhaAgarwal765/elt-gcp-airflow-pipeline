# elt-gcp-airflow-pipeline
# ELT Data Pipeline using Apache Airflow & Google Cloud Platform

This project demonstrates a basic ELT pipeline that processes 1 million+ records using Apache Airflow and Google BigQuery.

## 🔧 Tools & Technologies
- Apache Airflow (VM setup)
- Google Cloud Storage
- Google BigQuery
- Python
- CSV
- DAGs (Directed Acyclic Graphs)

## 📌 Project Workflow
1. Upload CSV file to GCP Cloud Storage
2. Airflow DAG:
   - Checks file existence
   - Loads data into BigQuery staging table
   - Transforms data into country-wise tables
3. Creates BigQuery views for reporting

## 📁 Directory Structure
- `dags/`: Contains Airflow DAGs
- `data/`: Sample CSV file
- `sql/`: SQL scripts for transformation
- `screenshots/`: DAG run, BigQuery table preview

## 🎯 Outcome
- Basic ELT pipeline setup completed
- Processed 1M+ records successfully
- Built views and reporting layer in BigQuery

## 📸 Screenshots
Include screenshots of:
- Airflow DAG in browser
- BigQuery tables
- Cloud Storage bucket

## ▶️ YouTube Reference
Based on this walkthrough: [Watch here](https://www.youtube.com/watch?v=pilPHlOVjII)
