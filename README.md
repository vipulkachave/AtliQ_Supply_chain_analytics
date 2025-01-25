
# **AtliQ Hardware - Sales, Finance and Supply Chain Analytics Project**

## **Project Overview**  
This project showcases the implementation of advanced **SQL-based analytics** for **AtliQ Hardware** to derive actionable insights across key domains, including **Sales**, **Finance**, and **Supply Chain**. The focus was on leveraging SQL capabilities to process and analyze large datasets while optimizing data retrieval and reporting processes.  

## **Project Objective**
This project is designed to analyze and extract valuable insights from the provided database. The database contains information about sales, products, customers, and regions for Atliq Hardware. I aim to address generate insights related to sales reports, market analysis, customer behavior, and supply chain forecasting. The objective of this project is to leverage SQL to analyze Atliq Hardware's sales data and generate key business insights that will help the management team make data-driven decisions.

The project involved working with approximately **1.43 million records** spread across multiple tables.

## **Problem statement**
Atliq Hardware is a hardware retail business that operates in multiple markets and offers a wide range of personal computers, mice, printers, and various other peripherals.
The business faces the challenge of analyzing large volumes of sales data across different branches and regions to gain actionable insights for decision-making. Currently, the business lacks a comprehensive data analysis solution to evaluate its financial performance and optimize its sales strategy.

## **Key Features and Techniques**

### **1. Data Modeling:**   
- Structured data using **Star Schema** and **Snowflake Schema** to support analytical and transactional requirements.  

### **2. Data Analytics and Reporting:**  
- Generated **Profit & Loss (P&L) Statements** to analyze revenue, costs, and profitability.  
- Created **User-Defined Functions**, such as `get_fiscal_year` & `get_fiscal_quarter`, to dynamically calculate fiscal year and fiscal quarter.  
- Designed **Gross Sales Reports** using **Stored Procedures** for efficient monthly sales analysis.  
- Developed reports identifying **Top Products and Customers** using advanced SQL techniques, including **Window Functions** (`ROW_NUMBER`, `RANK`, `DENSE_RANK`).

### **3. Query Techniques and Optimizations:**  
- **Complex Joins:** Connected data across multiple tables to create comprehensive reports.  
- **Common Table Expressions (CTEs):** Simplified and organized queries for clarity and reuse.  
- **Subqueries:** Performed dynamic calculations for row-level data.  
- **Window Functions:** Used for advanced analytics, such as calculating customer-wise net sales distribution and net sales percentage contribution.  
- **Views:** Created reusable database views to streamline query results and improve efficiency.

### **4. ETL Processes and Optimization:**  
- Designed and executed **Extract, Transform, Load (ETL)** workflows for data preparation and transformation.  
- Utilized indexing and query tuning to handle large datasets efficiently.

## **Tables Used:**  
The database comprises the following tables:  
- `dim_customer`  
- `dim_product`  
- `fact_sales_monthly`  
- `fact_gross_price`  
- `fact_pre_invoice_deductions`  
- `fact_post_invoice_deductions`  

### **Total Records:** Approximately **1.43 million**.

## **Technical Skills Gained:**  
- **SQL Queries:** Developed proficiency in crafting complex queries with joins, subqueries, and window functions.  
- **Data Extraction:** Mastered techniques to efficiently extract specific data points from large datasets.  
- **User-Defined Functions:** Designed custom functions for tasks like fiscal year calculations.  
- **Stored Procedures:** Automated repetitive tasks, such as generating monthly gross sales reports and assigning market badges based on turnover.  
- **Views:** Utilized database views for storing and reusing complex query results.  
- **CTEs and Window Functions:** Performed advanced data manipulations, including net sales calculations and ranking analysis.  

## **Soft Skills Gained:**  
- **Requirement Analysis:** Translated business needs into SQL queries and actionable reports.  

## **Technologies Used:**  
- **MySQL:** Database management and query execution.  
- **Stored Procedures, Views and User defined functions:** For automation and reusable computations.  

