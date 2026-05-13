# Data Engineering & Analytical Databases Portfolio

This repository contains technical documentation and architectural designs developed during my Master’s in Data Science at UOC.
The projects focus on building robust data infrastructures, from automated ETL processes to the implementation of complex Data Warehouse schemas.

## 📁 Projects Overview

### 1. Automated ETL Pipeline Design
**Documentation:** `ETL_Pipeline_Implementation_Pentaho.pdf`
* **Tools:** Pentaho Data Integration (Spoon), PostgreSQL.
* **Description:** Design and implementation of an end-to-end ETL workflow.
* **Key Engineering Tasks:**
    * Configuring a repository-based environment and dynamic variables for data sources.
    * Implementing data ingestion from large-scale raw files.
    * Automating data cleansing, type transformation, and loading into a relational target database.

### 2. Data Warehouse Architecture & SQL Modeling
**Documentation:** `Data_Warehouse_Schema_and_SQL_Implementation.pdf`
* **Tools:** PostgreSQL, SQL Server Management Studio (SSMS).
* **Description:** Engineering a complete analytical data environment for vehicle registration data.
* **Key Engineering Tasks:**
    * **Staging Layer:** Implementation of transient tables (`stg_`) for raw data processing.
    * **Star Schema Design:** Design and DDL implementation of Dimension tables (Date, Vehicle, Municipality, DGT Type) and Fact tables (`fact_vehicle_registration`).
    * **Data Integrity:** Handling primary keys, foreign key constraints, and relational cascading.
    * **Analytical Queries:** Development of advanced SQL queries to extract business metrics and verify data consistency.

## 🛠️ Technical Stack
* **Database Management:** PostgreSQL, SQL Server.
* **Data Integration:** Pentaho Spoon (Kettle).
* **Languages:** SQL (DDL/DML), Python (Pandas/NumPy for pre-processing).
* **Modeling:** Star Schema, Multidimensional Analysis (OLAP).

## ✉️ Contact
**Albert Carmona Hernández** [LinkedIn Profile](https://www.linkedin.com/in/albert-carmona-hernandez) | albertcarmonahernandez@gmail.com
