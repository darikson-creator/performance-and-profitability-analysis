# On-Premise Data Warehouse & Power BI Executive Dashboard

 ## 📌 Overview

This project presents a comprehensive Business Intelligence solution—from architectural schema design to automated data ingestion and executive reporting. The goal is to build an on-premise relational Data Warehouse in MySQL, automate batch synchronization using custom Python scripts, model a Star Schema with advanced DAX metrics, and deploy an interactive dashboard to Power BI Service for executive decision-making.

## 📁 Dataset

Source: Enterprise Operational Files (Excel / CSV)

Format: Flat files (CSV / XLSX)

Description: Contains operational records mapped across a 4-table relational model (sucursales, productos, ventas, costos), capturing transactional sales, product details, operational branch metadata, and associated cost structures.

 ## 🛠️ Tools & Technologies

Database & Warehousing: MySQL Workbench, SQL

ETL & Automation: Python (pandas, pymysql)

Business Intelligence & Data Modeling: Power BI Desktop, Power BI Service, DAX

Documentation & Presentation: Markdown & Gamma App (Executive Presentation)

 ## 🚀 Project Steps & Methodology

### 1. Database Architecture & Design (MySQL)

Designed a 4-table relational schema (sucursales, productos, ventas, costos) enforcing foreign key constraints and primary key relationships.

Configured tables to optimize query execution and ensure transactional data integrity.

### 2. Automated Python ETL Ingestion

Developed custom Python scripts (pandas, pymysql) for automated batch processing.

Implemented synchronization scripts to automatically parse raw incoming CSV/Excel files and ingest cleaned records into the MySQL Data Warehouse.

### 3. Advanced SQL Analysis & Data Validation

Executed SQL queries for business logic validation, temporal aggregations, and transactional integrity checks.

Utilized JOINs, subqueries, and window functions to audit operational metrics prior to BI loading.

### 4. Dimensional Modeling & Dashboard Development (Power BI)

Connected Power BI to the MySQL Data Warehouse.

Modeled a Star Schema with a dynamic Date Dimension (DimDate) linked to fact tables.

Authored custom DAX metrics for Key Performance Indicators (Total Revenue, Gross Margins, YoY/MoM comparative analysis).

Designed executive dashboard layouts optimized for performance and visual clarity.

### 5. Deployment & Executive Reporting (Power BI Service & Gamma)

Deployed the final interactive dashboard to Power BI Service for cloud availability and executive sharing.

Summarized high-level insights and strategic recommendations into an executive slide deck using Gamma AI.

 ## 📊 Dashboard Preview

### 📈  Key Results & Insights

Revenue & Profitability: Evaluated total revenues and gross margins across branches (sucursales) and product lines (productos).

Temporal Trends: Calculated YoY (Year-over-Year) and MoM (Month-over-Month) growth metrics to track business trajectory.

Cost Efficiency: Mapped cost metrics against transactional sales to identify low-margin operational areas.

 ## ⚙️ How to Run This Project

### Prerequisites:

Ensure you have the following installed on your machine:

Python 3.x

MySQL Server & MySQL Workbench

Power BI Desktop

Access to Power BI Service (optional for deployment)

---

## 🛠️ Workflow (Images)

### Create DB
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/1.%20Create%20DB.png)
 
### Query DB
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/2.%20Query%20DB.png)
 
### Semantic Model
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/3.%20Load%20tables%20to%20PBI.png)
 
### DAX Queries
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/4.%20DAX%20queries.png)
 
### New Data Uploaded with Python
![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/efb1685eb0afb3cf2c1ef8246c0f79328e80649c/5.%20New%20data%20upload%20with%20Py%202.png)

### PBI Report
![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/efb1685eb0afb3cf2c1ef8246c0f79328e80649c/6.%20Publish%20to%20PBI.png)

