# sql-data-warehouse-project
End-to-end Data Warehouse and Analytics project using SQL Server, ETL pipelines, Medallion Architecture, and Star Schema modeling.
The workflow includes:

Importing raw CSV data from ERP and CRM systems
Cleaning and transforming datasets
Designing a scalable dimensional model
Building analytical tables
Generating business insights using SQL

The final solution enables stakeholders to analyze:

Customer behavior
Product performance
Sales trends
Business KPIs


🏗️ Data Architecture

The project follows the Medallion Architecture approach using three layers:

🥉 Bronze Layer — Raw Data
Stores source data in its original format
Data is loaded directly from CSV files into SQL Server
Acts as the historical/raw ingestion layer
Key Features
Minimal transformation
Preserves original source data
Supports auditability and troubleshooting


🥈 Silver Layer — Cleaned & Transformed Data
Performs data cleansing and standardization
Removes duplicates and resolves data quality issues
Normalizes data for consistent analytics
Key Features
Data validation
Standardized formats
Business rule implementation
Improved data quality


🥇 Gold Layer — Business Ready Data
Contains analytical models optimized for reporting
Implements star schema design
Includes fact and dimension tables
Key Features
Fast analytical queries
BI-friendly structure
Optimized reporting datasets


📊 Project Objectives
Data Engineering Objectives

Build a scalable and maintainable SQL Server data warehouse that:

Integrates ERP and CRM datasets
Cleans and transforms raw data
Creates reusable ETL pipelines
Supports analytical reporting
Data Analytics Objectives

Develop SQL-based analytical solutions to provide insights into:

Sales performance
Customer segmentation
Product analytics
Revenue trends
Business growth metrics


🛠️ Technologies Used
Category	Tools & Technologies
Database	SQL Server Express
SQL IDE	SQL Server Management Studio (SSMS)
ETL	SQL Scripts
Data Modeling	Star Schema
