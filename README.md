# Data Pipeline: On-Prem SQL Server to Databricks & Power BI

## Project Overview

This project migrates data from an on-prem SQL Server to Databricks, enabling advanced data transformations and analytics. The processed data is visualized in Power BI to support business insights.

## Architecture Workflow

![Senior Project Workflow](https://github.com/user-attachments/assets/f57dd6ad-2bd2-43e2-8d16-a736afbca362)

## Tools & Technologies Used

- **On-Prem SQL Server** – Source database
- **Azure Data Factory** – ETL pipeline for data movement
- **Azure Data Lake Storage Gen2 (ADLS Gen2)** – Raw storage (Bronze Layer)
- **Databricks** – Managed data processing (Bronze, Silver, Gold tables)
- **Azure Key Vault** – Secure credentials and secrets management
- **Power BI** – Data visualization and reporting

## Repository Structure

```plaintext
├── notebooks/                 # Databricks notebooks for ETL & transformations
│   ├── bronze_layer_etl.dbc   # Ingest data into Bronze tables
│   ├── silver_layer_etl.dbc   # Clean & transform data into Silver tables
│   ├── gold_layer_etl.dbc     # Final transformations & aggregations
│
├── guide.md                   # Step-by-step guide on running the pipeline
├── README.md
```

## Additional Documentation
For detailed step-by-step instructions, check guide.md.  

Author: Sarah Dorny
📅 Project Start Date: 2025-02-10
