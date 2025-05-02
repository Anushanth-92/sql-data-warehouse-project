# 🏗️ Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project showcases a complete end-to-end data warehousing and analytics solution — from raw data ingestion to insightful reporting. Designed as a portfolio project, it emphasizes industry best practices in data engineering, ETL development, and data analysis.

---

## 📐 Data Architecture: Medallion Layers

This project follows the **Medallion Architecture** with a three-layered approach:

- **🔹 Bronze Layer**:  
  Stores raw data as-is from source systems. Data is ingested from CSV files into a SQL Server database.

- **🔸 Silver Layer**:  
  Applies data cleansing, standardization, and normalization techniques to prepare data for analysis.

- **🏅 Gold Layer**:  
  Contains business-ready data modeled in a star schema optimized for analytics and reporting.

---

## 📖 Project Overview

This project includes:

- **Data Architecture**: Medallion-based modern warehouse design.
- **ETL Pipelines**: Extract, transform, and load processes from raw CSVs to analytical models.
- **Data Modeling**: Implementation of dimension and fact tables.
- **Analytics & Reporting**: SQL-based reports for stakeholder insights.

---

## 🎯 Skills Demonstrated

This repository is perfect for showcasing skills in:

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics

---

## 🛠️ Tools & Resources

Everything you need is free and open source!

- **Datasets**: Sample ERP and CRM data in CSV format
- **SQL Server Express**: Lightweight SQL database engine
- **SQL Server Management Studio (SSMS)**: GUI for database development
- **GitHub**: Version control and collaboration
- **Draw.io**: For diagrams and architecture visuals
- **Notion**: Template and documentation management

---

## 🚀 Project Requirements

### 🔧 Building the Data Warehouse (Data Engineering)

- **Data Sources**: Two source systems (ERP and CRM) in CSV format
- **Data Quality**: Cleanse and standardize raw data
- **Integration**: Merge datasets into a single analytical model
- **Scope**: Use only the latest dataset; historization not required
- **Documentation**: Provide metadata and data model diagrams

### 📊 BI: Analytics & Reporting (Data Analysis)

Develop analytics using SQL to deliver insights on:

- Customer Behavior
- Product Performance
- Sales Trends

These reports support strategic, data-driven decision-making.

---

## 📂 Repository Structure


data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
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
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
