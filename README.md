# Ecommerce-intelligence-hub-powerbiproject
End-to-end E-Commerce Sales &amp; Customer Analytics solution built with Power BI, Power Query and DAX.
📊 Project Overview

E-Commerce Intelligence Hub is an end-to-end Power BI analytics project developed to transform raw e-commerce data into meaningful business insights.

The project analyzes sales performance, customer behavior, sales targets, Sales Manager performance, sales teams, countries, customer categories, order sources, and monthly sales trends.

The solution combines Power Query for data cleaning and transformation, data modeling for connecting business entities, and DAX for creating business metrics and performance calculations.

The final Power BI report provides an interactive environment where users can explore business performance through KPIs, charts, maps, slicers, drill-through pages, bookmarks, and Q&A.

🎯 Business Objective

The primary objective of this project is to help an e-commerce company understand:

How much revenue the business generated
Whether Sales POCs and Managers achieved their targets
Which Sales Teams are performing against their targets
Which countries generate the most sales and orders
How sales change month by month
Which order sources customers use
How customers are distributed across categories
Which customers have not placed orders
How Sales Managers perform across different countries
Where sales performance may require further attention
🗂️ Dataset

The project uses three main tables:

1. Orders

Contains transactional information such as:

Order ID
Customer ID
Order Datetime
Order Value
Order Source
Sales POC
Country
2. Customers

Contains customer-related information such as:

Customer ID
Customer details
Country
Gender
Age
Customer Category
3. Sales Targets

Contains sales-performance information such as:

Sales POC
Sales Manager
Sales Team
2023 Sales Target

The original business scenario covers customers across 14 countries, with 5 Sales Teams: Alpha, Beta, Gamma, Delta and Epsilon.

🧹 Data Preparation

The data was prepared using Power Query before building the report.

Key preparation steps included:

Imported all three datasets
Checked data types
Identified missing Order Source values
Replaced missing Order Source values with Website, based on the project requirement
Created the Sales Manager field by combining first and last names
Checked relationships between Customers, Orders and Sales Targets
Validated Customer IDs and Sales POCs
Prepared the data for analysis and visualization
🧠 Data Modeling

The Power BI model connects the major business entities:

Customers → Orders → Sales Targets

The model enables analysis of:

Customers and their orders
Orders handled by Sales POCs
Sales POCs and their Sales Managers
Sales Managers and their teams
Actual sales compared with assigned targets
📐 DAX & Analysis

DAX was used to create business metrics and calculated columns, including:

Total Sales
Total Orders
Total Customers
Average Order Value
Total Sales Target
Target Completion %
Sales by Sales POC
Target Bucket
Customers Who Did Not Order
% Customers Who Did Not Order
Manager-level performance
Team-level performance
Target Classification

Sales POCs were classified into:

Target Not Met
Target Met
Target Exceeded

This allows management to quickly identify performance against individual targets.

📈 Dashboard Analysis

The report covers multiple business perspectives.

Sales Performance
Total Sales
Total Orders
Sales Target
Target Achievement
Monthly Sales Trend
Sales Manager Analysis
Manager-wise sales
Manager target performance
Manager performance by country
Managers with the highest targets
Target shortfall analysis
Sales Team Analysis

Performance across:

Alpha
Beta
Gamma
Delta
Epsilon
Customer Analysis
Customer count by category
Average age by category
Customer order activity
Customers who did not place orders
Gender and category analysis
Country Analysis
Sales by country
Orders by country
Customers by country
Average Order Value by country
Sales Manager performance by country
Order Source Analysis

Analysis of orders coming from:

App
Website
WhatsApp
Other
🗺️ Interactive Power BI Features

The project also demonstrates several Power BI capabilities:

📊 KPI Cards
📈 Line Charts
🍩 Donut Charts
🗺️ Map Visualizations
🎛️ Slicers
🔍 Drill-through
🔖 Bookmarks
❓ Power BI Q&A
📱 Mobile Layout
Interactive filtering

A Country Sales Map also supports drill-through into Sales Manager-level performance for the selected country.
