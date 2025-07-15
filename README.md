# Data Warehouse and Analytics Project

---

Welcome to the **Data Warehouse and Analytics Project** repository!  This project demonstrates a comprehensive data warehousing solution built on SQL Server using medallion architecture principles. The implementation features end-to-end ETL processes, robust data modelling, and advanced analytics capabilities. Designed as a portfolio project, it showcases modern data engineering best practices and delivers actionable business insights.

---

## 🎯 Project Objectives

---

This project aims to build a real-world data warehouse that consolidates data from multiple operational systems ( **ERP**, **CRM**) into a centralised **SQL Server-based data warehouse**.

It supports:

-  **Tracking operational KPIs** for business intelligence (BI)
-  **Standardized reporting** across departments and systems
-  **Advanced analytics**, including BI dashboards and machine learning use cases
-  **Ad-hoc SQL queries** for custom insights and exploration

---  

## 🧩 Data Architecture

---

The architecture follows the **Medallion model**, which organises data in layered stages for scalable analytics and data quality management.
![Medallion Architecture Overview](docs/data_architecture.png)


- **Bronze Layer – Raw Data Ingestion**  
  Stores raw data exactly as received from source systems (ERP, CRM). Data is ingested from **CSV files** into **SQL Server staging tables** with no transformations, preserving the original format.

- **Silver Layer – Cleansed and Structured Data**  
  Transforms raw data through **cleansing, normalisation, and standardisation**. 

- **Gold Layer – Business-Ready Data Models**  
  Contains **refined and aggregated data** modelled in a **Star Schema** format. Designed for **BI dashboards, ad-hoc queries, and machine learning**, it includes calculated KPIs and logic aligned with business needs.






