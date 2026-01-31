# Azure Retail Data Engineering Project

## 📌 Overview
This project demonstrates an end-to-end Azure Data Engineering solution for a retail use case.
Data is ingested from multiple sources, processed using the Medallion Architecture, and visualized using Power BI.

## 🏗 Architecture
- Azure Data Factory (ADF) for data ingestion
- Azure Data Lake Storage Gen2 (ADLS)
- Databricks with PySpark & Delta Lake
- Bronze → Silver → Gold layers
- Power BI for reporting

## 📊 Data Sources
- Azure SQL Database (Transactions, Stores, Products)
- REST API (Customers – JSON format)

## 🔄 Data Flow
1. Ingest data using ADF
2. Store raw data in Bronze layer
3. Clean & transform data in Silver layer
4. Create business-ready data in Gold layer
5. Build Power BI dashboards

## 🛠 Technologies
- Azure Data Factory
- Azure Data Lake Gen2
- Databricks
- PySpark
- Delta Lake
- Power BI

## 🎯 Key Learnings
- Building production-grade data pipelines
- Implementing Medallion Architecture
- Working with multiple data sources
- Data modeling and reporting
