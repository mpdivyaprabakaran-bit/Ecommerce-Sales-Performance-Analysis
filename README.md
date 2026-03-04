# Ecommerce-Sales-Performance-Analysis
An end-to-end data analysis project using Excel and Power BI to identify profit leakages, regional performance, and the impact of discounts on an e-commerce dataset (2023-2024).

**Project Objective**:
The goal of this project was to develop a Business Intelligence dashboard to provide actionable insights into sales performance. By establishing relationships between sales facts and dimensional data (Customer, Product, and Store), I aimed to identify key drivers of revenue and areas of profit leakage.

**Dataset & Data Modeling**:
The project utilizes an e-commerce transaction dataset with a Star Schema architecture: 
Fact Table: Sales_Fact (Core transaction data including Sales ID, Date, and Customer ID). 
Dimension Tables: Customer_Dim, Product_Dim, and Store_Dim. 
Data Cleaning: I used Excel via Power Query to remove duplicates, handle null values, and engineer new columns like Profit Status and Profit_Margin.

**Key Insights**:
Financial Overview: Generated a total revenue of $2,173,944.27 with a total profit of $894,241.08 from 4,958 units sold. 
The "Discount Threshold": My analysis revealed that any discount exceeding 12% typically results in a negative net profit. 
Regional Leader: The North Region led all areas in sales volume, contributing $643,578.64 in revenue.
Channel Performance: Online stores outperformed both Flagship and Outlet physical locations.
Customer Demographics: The largest sales segment is Adults, followed by the elderly and young adults.

**Business Recommendations**:
Pricing Strategy: Maintain discounts below 10% to ensure profitability, as deeper discounts do not significantly increase the quantity sold.
Operational Improvement: Since most transactions are completed via Online or COD (Cash on Delivery), introducing targeted credit card offers could improve payment efficiency.
Profit Leakage Mitigation: Closely monitor transactions with discounts exceeding 20% to prevent negative profit margins.
