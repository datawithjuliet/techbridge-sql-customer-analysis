# TechBridge SQL Customer Analysis

## 📊 Project Overview

This project is part of the TechBridge Data Analytics Internship – Task 4: Introduction to SQL.

The objective of this project was to use SQL to answer basic business questions about a company's customers. The analysis focuses on customer demographics, locations, membership structure, spending patterns, customer churn, and high-value customers.

---

## 🎯 Project Objectives

The project answers the following business questions:

1. How many customers are in the dataset?
2. Which countries do the customers come from?
3. How many customers are from the United Kingdom?
4. How many customers belong to each membership tier?
5. Who are the top 10 customers based on total spending?
6. What is the average age of customers?
7. What is the average amount spent by a customer?
8. How much have all customers spent in total?
9. How many customers have churned?
10. How many customers have spent more than $1,000?

---

## 🛠️ Tools Used

- MySQL Workbench
- SQL
- Microsoft Word

---

## 📁 Dataset

The dataset contains customer information, including:

- Customer ID
- Country
- Age
- Gender
- Membership Tier
- Registration Date
- Total Spend
- Churn Status

The dataset also contains additional customer-related information used for analysis.

---

## 🔍 SQL Skills Demonstrated

This project demonstrates the following SQL skills:

- `SELECT`
- `DISTINCT`
- `WHERE`
- `COUNT()`
- `AVG()`
- `SUM()`
- `GROUP BY`
- `ORDER BY`
- `DESC`
- `LIMIT`

---

## 📈 Key Findings

- The dataset contains **8,000 customers**.
- The United Kingdom has **800 customers**.
- The United States is the largest customer market with **2,509 customers**.
- The Free membership tier has the highest number of customers with **4,443 members**.
- The average customer age is **35.62 years**.
- The average customer spending is **$1,558.64**.
- Total customer spending is **$12,469,138.80**.
- A total of **715 customers have churned**.
- **3,549 customers** have spent more than **$1,000**.

---

## 💡 Business Insights

The analysis shows that the company has a large and diverse international customer base. The United States represents the largest customer market. The Free membership tier contains the majority of customers, which may present an opportunity to convert customers to paid membership tiers.

A significant number of customers have spent more than $1,000, indicating a strong group of high-value customers. Customer churn should also be monitored to better understand customer retention and improve long-term business performance.

---

## 📂 Project Structure

```text
techbridge-sql-customer-analysis/
│
├── dataset/
│   └── TechBridge_Task_4_Customers.csv
│
├── sql_queries/
│   └── customer_analysis.sql
│
├── screenshots/
│   └── SQL query results
│
├── report/
│   └── Juliet_Task_4_SQL_Basics.pdf
│
└── README.md
