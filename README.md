# Customer Behavior & Subscription Analysis Dashboard

An end-to-end Data Analytics project focused on understanding customer purchasing behavior, revenue patterns, product performance, customer segments, and subscription trends.

## 📊 Project Overview

This project analyzes **3,900 customer records** to identify meaningful business insights from customer purchases, demographics, product categories, reviews, and subscription behavior.

The project follows a complete data analytics workflow:

**Data Cleaning → SQL Analysis → Data Transformation → Power BI Dashboard → Business Insights**

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **PostgreSQL**
- **SQL**
- **Power BI**
- **DAX**

## 🔍 Key Analysis

- Customer purchasing behavior
- Revenue by product category
- Sales by product category
- Revenue by age group
- Customer subscription behavior
- Customer segmentation
- Average purchase amount
- Average review rating
- Product performance
- Subscription trends

## 🐍 Python & Pandas

Python and Pandas were used for:

- Data cleaning
- Handling missing values
- Data transformation
- Data type processing
- Preparing the dataset for SQL analysis

## 🗄️ SQL Analysis

PostgreSQL was used to perform analytical queries using:

- `SELECT`
- `WHERE`
- `GROUP BY`
- Aggregate Functions
- `CASE WHEN`
- CTEs
- Window Functions
- `ROW_NUMBER()`
- Filtering and segmentation

These queries were used to identify customer, product, revenue, and subscription patterns.

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created using **DAX measures, KPI cards, slicers, and charts**.

### Dashboard Features

- Total Customer KPI
- Average Purchase Amount
- Average Review Rating
- Subscription Rate
- Subscription Status Analysis
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Interactive Slicers
- Key Business Insights

## 💡 Key Insights

- **Clothing** generates the highest revenue among the analyzed categories.
- **Middle-aged customers** contribute the highest revenue among the age groups.
- The overall **subscription rate is 27%**, while 73% of customers are unsubscribed.
- Customer and product-level analysis reveals differences in purchasing and revenue patterns across segments.

## 📂 Project Structure

```text
customer-behavior-subscription-analysis/
│
├── README.md
├── customer_behaviour.sql
├── customer_shopping_behavior.csv
├── Retail_Customer_Behavior_Analysis.ipynb
└── customer_behaviour_dashboard.pbix
