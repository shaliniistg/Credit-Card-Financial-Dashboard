# 📊 Credit Card Financial Dashboard | Power BI & MySQL

## 📌 Project Overview

This project demonstrates an end-to-end Business Intelligence workflow using **MySQL** and **Power BI**. The objective was to analyze credit card customer and transaction data to uncover revenue trends, customer demographics, spending behavior, and card performance through interactive dashboards.

Instead of importing CSV files directly into Power BI, the data was first stored in a MySQL database, transformed using SQL, connected to Power BI via the MySQL Connector, cleaned in Power Query, modeled with relationships, and analyzed using DAX measures.

---

## 🛠️ Tools & Technologies

- Power BI
- MySQL
- SQL
- Power Query
- DAX
- MySQL Connector

---

## 📂 Project Workflow

```text
CSV Dataset
      │
      ▼
MySQL Database
      │
      ▼
SQL Data Cleaning & Transformation
      │
      ▼
Power BI (MySQL Connector)
      │
      ▼
Power Query (ETL)
      │
      ▼
Data Modeling
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
```

---

## 📊 Dashboard Preview

### Credit Card Report

![Credit Card Report](Dashboard%20Screenshots/Credit%20Card%20Report.png)

### Customer Report

![Customer Report](Dashboard%20Screenshots/Customer%20Report.png)

---

## 📈 Dashboard Highlights

- Revenue Performance Analysis
- Weekly Revenue Comparison
- Customer Demographics
- Card Category Performance
- Expense Category Analysis
- Payment Method Analysis
- Quarterly Performance
- State-wise Revenue Analysis

---

## 🗄️ Database

Two relational tables were created in MySQL:

- `cust_detail`
- `cc_detail`

The tables were connected inside Power BI using **Client_Num**.

---

## ⚙️ ETL Process

- Imported raw CSV files into MySQL
- Created relational database tables
- Converted text dates into SQL DATE format using `STR_TO_DATE()`
- Used a temporary table to resolve date import issues
- Connected MySQL to Power BI
- Cleaned and transformed data using Power Query
- Built the data model and DAX measures
- Refreshed the dashboard after inserting additional weekly records into MySQL

---

## 📊 Key KPIs

- Total Revenue
- Current Week Revenue
- Previous Week Revenue
- Week-over-Week Growth
- Total Interest Earned
- Total Transaction Amount
- Total Transaction Count

---

## 💼 Skills Demonstrated

- SQL
- MySQL
- Data Cleaning
- ETL
- Power Query
- Data Modeling
- DAX
- Dashboard Development
- Business Intelligence
- Data Visualization

---

## 📁 Repository Structure

```text
Credit-Card-Financial-Dashboard
│
├── Credit_Card_Financial_Dashboard.pbix
├── README.md
├── Business_Insights.md
├── DAX_Measures.md
├── SQL
├── Dataset
└── Dashboard Screenshots
```

---

## 🚀 Future Improvements

- Implement Incremental Refresh
- Add Row-Level Security (RLS)
- Create Drill-through Pages
- Connect to a live SQL Server
- Build Mobile-Optimized Dashboard
