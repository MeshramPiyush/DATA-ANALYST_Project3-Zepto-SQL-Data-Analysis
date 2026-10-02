# DATA-ANALYST_Project3-Zepto-SQL-Data-Analysis
# Zepto SQL Data Analysis Project

## 📌 Overview

This project analyzes Zepto product data using SQL Server and SQL queries.

The project follows a data analytics workflow:

**CSV Dataset → SQL Server → Data Exploration → Data Cleaning → SQL Analysis → Business Insights**

The goal is to analyze product pricing, discounts, stock availability, inventory, product value, and category-level performance to solve business problems.

## 📊 Dataset

The dataset contains Zepto product information with the following columns:

- SKU ID
- Product Category
- Product Name
- MRP
- Discount Percentage
- Available Quantity
- Discounted Selling Price
- Weight in Grams
- Out of Stock
- Quantity

## 🛠️ Tools Used

- **Microsoft SQL Server** – Database and data analysis
- **SSMS** – SQL database management and query execution
- **SQL** – Data exploration, cleaning and business analysis
- **CSV** – Source dataset
- **GitHub** – Project documentation and version control

## 🔄 Project Workflow

### 1. SQL Server

The CSV dataset was imported into Microsoft SQL Server and stored in a table named `zepto`.

The SQL script includes:

- Database creation
- Table creation
- Data exploration
- NULL value checking
- Product category analysis
- Stock availability analysis
- Duplicate product analysis

### 2. Data Cleaning

The data was cleaned using SQL by:

- Identifying products with zero MRP
- Removing records where MRP was zero
- Converting MRP and discounted selling prices from paise to rupees

### 3. SQL Analysis

SQL queries were used to analyze:

- Top products based on discount percentage
- High-MRP products that are out of stock
- Estimated revenue by category
- High-MRP products with low discounts
- Categories with the highest average discounts
- Price per gram
- Product weight categories
- Total inventory weight by category

## 📈 Business Analysis

The SQL analysis provides insights into:

- Product pricing
- Discount strategies
- Stock availability
- Estimated category revenue
- Product value
- Inventory levels
- Product weight
- Category-level discount patterns

## 💡 Key Results

The analysis helps identify high-discount products, high-MRP out-of-stock products, categories with higher average discounts, estimated revenue by category, best-value products based on price per gram, and total inventory weight across categories.

## 📁 Project Structure

```text
Zepto-SQL-Data-Analysis/
│
├── 01 zepto_v2.csv
│
├── 02 Zepto_SQL_data_analysis.sql
│
└── README.md
