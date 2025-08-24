SQL Data Warehouse Project
This project demonstrates a comprehensive data warehousing and analytics solution, built from scratch to consolidate and analyze data for actionable insights. It highlights best practices in data engineering and analytics, tailored to my experience as a Data Engineer Trainee.
Data Architecture
The data architecture follows the Medallion Architecture with Bronze, Silver, and Gold layers:

Bronze Layer: Stores raw data as ingested from source systems (e.g., CSV files into SQL Server).
Silver Layer: Includes data cleansing, standardization, and normalization for analysis readiness.
Gold Layer: Houses business-ready data modeled into a star schema for reporting and analytics.

Project Overview
This project involves:

Data Architecture: Designing a modern data warehouse using Medallion Architecture.
ETL Pipelines: Extracting, transforming, and loading data from source systems.
Data Modeling: Developing fact and dimension tables optimized for analytical queries.
Analytics & Reporting: Creating SQL-based reports and dashboards for insights.

This repository serves as a portfolio piece to showcase expertise in:

SQL Development
Data Engineering
ETL Pipeline Development
Data Modeling
Data Analytics

Project Requirements
Building the Data Warehouse (Data Engineering)

Objective: Develop a modern data warehouse using SQL Server to consolidate sales and operational data for analytical reporting.
Specifications:
Data Sources: Import data from ERP and CRM systems (provided as CSV files).
Data Quality: Cleanse and resolve quality issues prior to analysis.
Integration: Combine sources into a single data model for analytical queries.
Scope: Focus on the latest dataset; historization not required.
Documentation: Provide clear data model documentation for stakeholders.



Analytics & Reporting (Data Analysis)

Objective: Deliver SQL-based analytics for insights into:
Customer Behavior, Product Performance,Sales Trends,These insights support strategic decision-making.


Repository Structure
sql-data-warehouse-project/
│
├── datasets/           # Raw datasets (ERP and CRM data)
├── docs/               # Project documentation and architecture details
│   ├── etl.drawio     # ETL process diagram
│   ├── data_architecture.drawio  # Project architecture
│   ├── data_catalog.md  # Dataset metadata
│   ├── data_flow.drawio  # Data flow diagram
│   ├── data_models.drawio  # Star schema models
│   ├── naming-conventions.md  # Naming guidelines
├── scripts/            # SQL scripts for ETL and transformations
│   ├── bronze/        # Raw data ingestion scripts
│   ├── silver/        # Data cleansing scripts
│   ├── gold/          # Analytical model scripts
├── tests/              # Test scripts and quality checks
├── README.md           # Project overview
├── LICENSE             # License information
├── .gitignore          # Ignored files
└── requirements.txt    # Project dependencies

Tools

Datasets: CSV files for ERP and CRM data.
SQL Server Express: Lightweight server for the database.
SQL Server Management Studio (SSMS): GUI for database management.
Git Repository: For version control and collaboration.
DrawIO: For designing architecture and data models.
