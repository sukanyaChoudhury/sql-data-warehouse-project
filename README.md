# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

## 🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
![data_architecture](https://github.com/user-attachments/assets/f18708ca-3c4f-4a74-bea1-2fae69557a42)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 📖 Project Overview

This project involves:
1. **Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
2. **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

## 🚀 Project Requirements
**Building the Data Warehouse (Data Engineering)**
## Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.
## Specifications
- Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files. In Bronze layer.
- Data Quality: Cleanse and resolve data quality issues prior to analysis. In Silver Layer
- Integration: Combine both sources into a single, user-friendly data model designed for analytical queries. In Gold Layer.
- Scope: Focus on the latest dataset only; historization of data is not required.
- Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
- Scripts and Documentation can be found under respective folders.

## Data Layers Details
<img width="728" alt="data_layers1" src="https://github.com/user-attachments/assets/3c3f4de2-cd25-4e5c-94a2-cceac3c2f2af" />

<img width="720" alt="data_layers2" src="https://github.com/user-attachments/assets/578ef490-63e3-478e-9905-c4d8b9dd4b18" />


## Data Flow
![data_flow](https://github.com/user-attachments/assets/b8b7e1fb-8314-4df7-950d-21eb545f5632)

## Data Integration:
How the data from different source systems are integrated to create dimension tables:


![data_integration](https://github.com/user-attachments/assets/71b6cbbb-7caa-493b-a4c5-21722c871d7d)

## Final Data Model
Final Star schema data model after combining tables from different sources showing one fact table and two dimension tables:
![data_model](https://github.com/user-attachments/assets/0e4b028d-2953-4c53-8e74-2519a0c36409)

