# # 🚀 E-Commerce Intelligence Hub — Power BI

> End-to-end E-Commerce Sales & Customer Analytics project built with Power BI, Power Query and DAX.

## 📌 Project Overview

This project analyzes e-commerce sales, customer behavior, sales targets and Sales Manager performance using Power BI.

The analysis covers sales across countries, Sales Teams, Sales Managers, customer categories and order sources. The goal is to transform raw transactional data into interactive business insights.

## 🎯 Business Objectives

- Analyze overall sales and order performance
- Compare actual sales with Sales POC targets
- Evaluate Sales Manager and Sales Team performance
- Analyze sales across countries
- Identify monthly sales trends
- Understand customer category and gender behavior
- Analyze order sources
- Identify customers who did not place orders

## 📂 Dataset

The project contains three tables:

### Orders
Transactional order information including Order ID, Customer ID, Order Value, Order Source, Sales POC, Country and Order Datetime.

### Customers
Customer information including Customer ID, Country, Gender, Age and Customer Category.

### Sales Targets
Sales POC, Sales Manager, Sales Team and 2023 Sales Target information.

## 🧹 Data Preparation

Power Query was used to:

- Clean and transform the source data
- Handle missing Order Source values
- Replace missing Order Source with Website as required
- Create the Sales Manager field
- Validate the data before analysis

## 🧠 Data Model

The report connects:

**Customers → Orders → Sales Targets**

This enables analysis of customer activity, transactions, Sales POCs, Sales Managers and targets within a single Power BI model.

## 📊 Dashboard & Analysis

The report provides analysis of:

- Sales & Orders
- Target Achievement
- Sales Manager Performance
- Sales Team Performance
- Country Performance
- Monthly Sales Trends
- Customer Categories
- Customers Who Did Not Order
- Order Sources
- Average Order Value

## ⚡ Power BI Features

- DAX Measures
- Power Query
- Data Modeling
- KPI Cards
- Interactive Slicers
- Maps
- Drill-through
- Bookmarks
- Power BI Q&A
- Mobile Layout

## 💡 Key Insights

- Total Sales: **₹12.28M**
- Total Orders: **2,500**
- Total Customers: **2,500**
- Overall Target Achievement: **95.83%**
- Customers Without Orders: **1,047 (41.88%)**
- Highest Sales Month: **November**
- Highest Sales Country: **USA**

## 🛠️ Tools & Technologies

**Power BI | Power Query | DAX | Excel | Data Modeling | Data Visualization**.
