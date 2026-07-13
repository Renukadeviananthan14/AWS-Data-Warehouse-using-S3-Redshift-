
# 🚀 Cloud Sales Data Warehouse using AWS

## 📌 Project Overview
This project demonstrates an end-to-end cloud data warehouse solution using **Amazon S3 and Amazon Redshift**.  
Raw sales data is ingested, transformed, and modeled into a structured format for business analytics using SQL.

---

## 🏗️ Architecture
- Raw Data Storage → Amazon S3  
- Data Ingestion → Amazon Redshift 
- Staging Layer → Raw data processing  
- Transformation Layer → Data cleaning & deduplication  
- Data Model → Star Schema (Fact & Dimension tables)  
- Analytics Layer → SQL-based insights  

---

## 🛠️ Tech Stack
- Amazon S3  
- Amazon Redshift  
- SQL  
- AWS IAM  

---

## 📊 Dataset Features
- Order ID  
- Order Date  
- Customer Name  
- City  
- Product Name  
- Category  
- Quantity  
- Price  
- Payment Mode  
- Order Status  

---

## 🔄 Data Processing Steps
1. Loaded raw CSV data into **Amazon S3**
2. Ingest data into Redshift staging table
3. Cleaned data:
   - Removed duplicates
   - Handled missing values
   - Filtered cancelled orders
4. Created **Star Schema design**
   - Fact Table: Sales transactions
   - Dimension Tables: Customers, Products, Date
5. Built final analytics-ready dataset

---

## 📊 Business Insights Generated
- Total revenue analysis  
- City-wise sales performance  
- Product category performance  
- Top-selling products  
- Payment mode distribution  
- Time-based sales trends  

---

## 📈 Key Learnings
- Real-world data warehouse design using Star Schema  
- ETL pipeline using AWS services  
- Data cleaning and transformation using SQL  
- Role of staging vs final fact tables in analytics  

---

## 🚀 Future Improvements
- Automate pipeline using AWS Glue / Airflow  
- Add dashboard using Power BI or QuickSight  
- Extend dataset with customer behavior analytics  

---

## 👨‍💻 Author
Built as a hands-on learning project in AWS Data Engineering.

---

## ⭐ Note
This project is part of my learning journey in Cloud Data Engineering and SQL-based analytics.
