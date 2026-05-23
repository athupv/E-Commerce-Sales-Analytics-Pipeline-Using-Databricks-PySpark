# E-Commerce Sales Analytics Pipeline Using Databricks & PySpark

## Project Overview
This project demonstrates an end-to-end data engineering and analytics pipeline built using Databricks, PySpark, Spark SQL, and Delta Lake. The pipeline processes e-commerce sales data, performs data transformation and analytics, and generates business insights from large-scale retail datasets.

---

## Technologies Used
- Databricks
- Apache Spark
- PySpark
- Spark SQL
- Delta Lake
- Python
- Git & GitHub

---

## Project Workflow

Raw CSV Dataset  
→ Data Ingestion  
→ Data Cleaning using PySpark  
→ Data Transformation  
→ Spark SQL Analytics  
→ Delta Table Storage  
→ Business Insights & Reporting

---

## Dataset Details

The dataset contains e-commerce sales records with:

- Order ID
- Customer Name
- Product
- Category
- Quantity
- Price
- Total Revenue
- Order Date
- City
- Payment Method
- Delivery Status

---

## Features Implemented

### Data Ingestion
- Uploaded CSV dataset into Databricks
- Created structured tables from raw data

### Data Cleaning
- Removed null values
- Standardized data types
- Processed structured columns

### Data Transformation
- Calculated total revenue
- Aggregated category-wise sales
- Created city-wise revenue reports
- Generated product sales analytics

### Analytics Performed
- Top-selling products
- Revenue by city
- Delivery status analysis
- Payment method analysis
- Product category performance

### Delta Lake Integration
- Stored transformed data as Delta Tables
- Implemented overwrite mode for ETL workflow
