# RFM-customer-segmentation-sqlRFM Customer Segmentation using SQL
Project Overview

This project performs customer segmentation using the RFM model (Recency, Frequency, Monetary).

RFM analysis is a widely used marketing technique that helps businesses understand customer purchasing behavior and identify high-value customers.

Using SQL, customers are segmented based on:

Recency – How recently a customer made a purchase

Frequency – How often the customer makes purchases

Monetary Value – How much money the customer spends

These metrics help businesses design targeted marketing strategies and improve customer retention.

Dataset

The dataset used in this project is an E-commerce transactions dataset (2010-2011) containing:

Customer ID

Invoice number

Invoice date

Product description

Quantity purchased

Unit price

Country

Each row represents a transaction made by a customer.

Tools & Technologies

SQL

Excel (for dataset exploration)

GitHub (for project version control)

Project Workflow
1 Data Cleaning

Removed null Customer IDs

Removed cancelled transactions

Checked for negative quantities

2 Customer Aggregation

Transactions were aggregated at the customer level to calculate purchasing behaviour.

3 Recency Calculation

Recency was calculated as the number of days since the customer's last purchase.

4 Frequency Calculation

Frequency represents the total number of purchases made by a customer.

5 Monetary Calculation

Monetary value represents the total amount spent by the customer.

6 RFM Score Calculation

Each customer was assigned scores for Recency, Frequency and Monetary values.

7 Customer Segmentation

Customers were grouped into segments such as:

Champions

Loyal Customers

Potential Loyalists

At Risk Customers

Lost Customers

Example Business Insights

Identified high value customers who generate the most revenue.

Detected customers at risk of churn due to long inactivity.

Recognized loyal customers with frequent purchases.

Helped identify customers suitable for targeted marketing campaigns.

SQL Concepts Used

This project demonstrates the following SQL skills:

GROUP BY

Aggregate Functions

Window Functions

CASE Statements

Common Table Expressions (CTE)

Date Calculations

Data Aggregation

Project Structure
rfm-customer-segmentation-sql
│
├── dataset
│   └── ecommerce_data.csv
│
├── sql_queries
│   ├── 01_data_cleaning.sql
│   ├── 02_rfm_calculation.sql
│   └── 03_customer_segmentation.sql
│
└── README.md
Business Value

RFM segmentation helps businesses:

Improve customer retention

Increase marketing efficiency

Identify high value customers

Personalize promotional campaigns

Author

Vedant Sharma
Aspiring Data Analyst skilled in SQL, Power BI and Excel
