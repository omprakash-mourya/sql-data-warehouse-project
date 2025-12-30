# Data Warehouse and Analytics Project for mercedes benz sales data

Welcome to the **Data Warehouse and Analytics Project** repository.  
This project demonstrates an end-to-end **modern data warehousing and analytics solution for mercedes benz sales data** using SQL Server, following industry-standard data engineering practices.

This repository is built as a **portfolio-grade project** to showcase practical skills in data engineering, data modeling, and analytics.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** approach with three layers:

**Bronze → Silver → Gold**

---   

### Layers Overview

1. **Bronze Layer**
   - Stores raw data ingested directly from source systems
   - Data is loaded from CSV files without transformations
   - Serves as a landing and audit layer

2. **Silver Layer**
   - Performs data cleansing, standardization, and normalization
   - Fixes data quality issues
   - Prepares data for analytical use

3. **Gold Layer**
   - Contains business-ready data
   - Modeled using a star schema
   - Optimized for reporting and analytics

---

## 📖 Project Overview

This project covers the complete lifecycle of a data warehouse:

1. **Data Architecture**
   - Design of a modern data warehouse using Medallion Architecture

2. **ETL Pipelines**
   - Extracting data from ERP and CRM CSV sources
   - Transforming and cleaning data using SQL
   - Loading curated data into analytical tables

3. **Data Modeling**
   - Creation of fact and dimension tables
   - Star schema design for efficient querying

4. **Analytics & Reporting**
   - SQL-based analysis for business insights
   - Queries focused on sales, customers, and products

### Skills Demonstrated
- SQL Development  
- Data Engineering  
- Data Warehousing  
- ETL Design  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Technologies

All tools used in this project are free:

- SQL Server Express
- SQL Server Management Studio (SSMS)
- Draw.io
- Git & GitHub

---

## 🚀 Project Requirements

### Data Warehouse (Data Engineering)

#### Objective
Build a modern SQL Server–based data warehouse that consolidates sales data from multiple sources to enable analytical reporting and decision-making.

#### Specifications
- **Data Sources**
  - ERP data (CSV files)
  - CRM data (CSV files)

- **Data Quality**
  - Handle missing values
  - Standardize formats
  - Resolve key mismatches

- **Integration**
  - Merge ERP and CRM data into a unified analytical model

- **Scope**
  - Focus only on the latest data
  - No historization or slowly changing dimensions

- **Documentation**
  - Clear documentation of tables, fields, and transformations

---

### BI & Analytics (Data Analysis)

#### Objective
Develop SQL-based analytics to provide insights into:

- Customer Behavior
- Product Performance
- Sales Trends

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality checks files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
```
---

## 🌟 About Me

I am **Omprakash**, a final-year undergraduate student in **Chemical Engineering at IIT Bombay**, transitioning into **Data Science and Data Engineering**.

This project reflects hands-on experience with:
- SQL-based data warehousing
- ETL pipelines
- Analytical data modeling
- Business-oriented analytics

The focus is on building real, production-style data systems.