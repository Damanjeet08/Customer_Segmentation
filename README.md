# Customer_Segmentation
📊 Customer Segmentation Analysis for Retail Sales

📌 Overview

This project performs Customer Segmentation for retail sales data using the RFM (Recency, Frequency, Monetary) technique. It leverages SQL for data extraction & transformation and Tableau for dashboard visualization. The goal is to classify customers into meaningful segments to help businesses make data-driven marketing decisions.

🎯 Objectives

-Analyze historical customer transactions to uncover purchasing patterns.

-Segment customers based on Recency, Frequency, and Monetary value.

-Identify high-value customers and those at risk of churn.

-Provide actionable insights for targeted marketing campaigns.

📂 Dataset

Source: sales_data_sample.csv

Records: 2,823 transactions

-->Key Fields:

ORDERNUMBER — Unique order identifier

CUSTOMERNAME — Customer name

ORDERDATE — Date of purchase

SALES — Transaction amount

PRODUCTLINE, COUNTRY, STATUS, DEALSIZE

🛠️ Tools & Technologies

-Languages: SQL

-Visualization: Tableau

-Data Analysis: Python (optional for RFM calculations)

-Libraries (Python): Pandas, NumPy, Matplotlib, Seaborn

📊 Methodology

-->Data Exploration

Checked unique values for key columns.

Identified data ranges and missing values.

-->RFM Analysis

Recency: Days since last purchase.

Frequency: Number of unique orders.

Monetary: Total spend.

-->Segmentation Rules

Champions

Loyal Customers

Potential Loyalists

At Risk

Lost Customers

-->Visualization

Created a Tableau dashboard to present insights interactively.

📈 Results

-Top Segments: Champions & Loyal Customers contributed ~60% of total revenue.
-At Risk Customers: Identified ~15% who haven’t purchased recently.
-Revenue Insights: High-value customers are concentrated in specific product lines and regions.

📌 Key Insights

-Personalized campaigns for Champions can increase upselling opportunities.
-Reactivation strategies needed for At Risk customers.
-Certain regions have high sales potential but low frequency — opportunity for targeted marketing.
