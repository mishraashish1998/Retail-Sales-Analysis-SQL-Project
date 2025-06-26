# 🛒 Retail Sales Analysis – SQL Project

## 📌 Project Overview

**Project Title**: Retail Sales Analysis  
**Database**: `sql_project_p2`  

This project demonstrates SQL skills typically used by data analysts to explore, clean, and analyze retail sales data. You’ll set up a retail database, perform EDA, and answer key business questions via SQL queries. Ideal for beginners looking to build a solid foundation in SQL.

---

## 🎯 Objectives

- **Set up a retail sales database** with provided data.
- **Data Cleaning**: Handle missing/null values.
- **Exploratory Data Analysis (EDA)**: Understand the dataset.
- **Business Analysis**: Use SQL queries to derive insights.

---

## 🗂️ Project Structure

### 1. 🏗️ Database Setup

- **Create Database**:  
  ```sql
  CREATE DATABASE sql_project_p2;
  
## Step 2: Create the retail_sales Table
```sql
CREATE TABLE retail_sales (
    transactions_id INT PRIMARY KEY,
    sale_date DATE,	
    sale_time TIME,
    customer_id INT,	
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,	
    cogs FLOAT,
    total_sale FLOAT
);

