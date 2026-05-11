# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

## 🏗️ Data Architecture
The data architecture for this project follows the Medallion Architecture (Bronze, Silver, and Gold layers):
- **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server database.
- **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
- **Gold Layer**: Houses business-ready data modeled into a star schema optimized for reporting and analytics.

## 📖 Project Overview
This project involves:
- **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture (Bronze, Silver, and Gold layers).
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for showcasing expertise in:
- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

## 🛠️ Tools & Technologies
- **SQL Server Express**: Lightweight server for hosting the SQL database.
- **SQL Server Management Studio (SSMS)**: GUI for managing and interacting with databases.
- **DrawIO**: Used for designing data architecture, models, flows, and diagrams.
- **Datasets**: CSV files representing ERP and CRM data.

## 🚀 Project Requirements

### 1. Building the Data Warehouse (Data Engineering)
**Objective**: Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**:
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### 2. Analytics & Reporting (Data Analysis)
**Objective**: Develop SQL-based analytics to deliver detailed insights into:
- Customer Behavior
- Product Performance
- Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making. (Refer to `docs/requirements.md` if available).

## 📂 Repository Structure
```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture.png           # Architecture diagram
│   ├── data_catalog.md                 # Catalog of datasets and metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_integration.drawio         # Data integration diagram
│
├── scripts/                            # SQL scripts for ETL, transformations, and analytics
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│   ├── analytics/                      # SQL scripts for data exploration, analytics, and reporting
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
└── .gitignore                          # Files and directories ignored by Git
```

## 🌟 Acknowledgments
This project is based on the comprehensive tutorials and resources provided by [Data With Baraa](https://github.com/DataWithBaraa). Special thanks to Baraa Khatib Salkini for his excellent materials on SQL Data Warehousing and Analytics. You can check out his content on YouTube and LinkedIn.

## 🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
