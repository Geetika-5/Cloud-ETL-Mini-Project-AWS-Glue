# Cloud ETL Mini Project – AWS Glue Style

## 📌 Overview
This project is a lightweight, AWS Glue–inspired ETL pipeline built using Python.
It simulates cloud-based data ingestion, transformation, and loading workflows
commonly used in AWS data engineering projects.

## 🏗 Architecture (Simulated)
- Raw Data Layer → S3 (simulated using local folders)
- ETL Job → AWS Glue Job (Python-based)
- Curated Layer → S3 curated zone (local output)

## 🧩 Project Structure
```text
cloud-etl-mini-project/
├── data/
│   ├── raw/
│   └── processed/
├── src/
│   └── glue_job.py
├── config/
│   └── config.yaml
├── requirements.txt
└── README.md

### 🔄 ETL Flow

Extract raw CSV data from the raw layer
Transform data (cleaning, standardization, enrichment)
Load curated data into the processed layer
Log row counts for basic data validation

### 🛠 Tech Stack

Python
Pandas
YAML
AWS Glue (simulated)
AWS S3 (simulated)