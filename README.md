🏦 Bank Customer Churn Analysis (Power BI)
📌 Overview

This project analyzes customer churn behavior in a banking dataset using Microsoft Power BI Desktop. The objective is to identify patterns behind customer attrition and provide actionable insights to improve retention.

🎯 Objectives
Analyze why customers leave the bank
Identify high-risk customer segments
Build interactive dashboards for decision-making
Provide business recommendations to improve retention
📁 Dataset

The dataset consists of multiple tables structured into a Star Schema:

Fact Table
Bank_Churn – customer data (age, balance, tenure, churn status)
Dimension Tables
CustomerInfo
Geography
Gender
CreditCard
ActiveCustomer
ExitCustomer
🧹 Data Cleaning
Removed duplicate records
Handled missing values
Standardized column names
Fixed data types
Ensured consistency in IDs
🏗️ Data Modeling
Implemented Star Schema
Created one-to-many relationships
Connected dimension tables to fact table
Optimized model by hiding ID columns
📐 DAX Calculations
Calculated Columns
Age Group
Tenure Category
Balance Status
Measures
Total Customers
Exited Customers
Retention Rate (%)
Exit Rate (%)
Active Customer %
Average Balance
Average Salary
📊 Dashboard
📄 Page 1 – Customer Overview
KPI Cards (Total Customers, Retention Rate, Active %)
Gender Distribution
Customers by Geography
Age Group Distribution
📄 Page 2 – Churn Analysis
Exited vs Retained Customers
Churn by Geography & Gender
Funnel (Active → Inactive → Exited)
Average Balance vs Age
📄 Page 3 – Product & Credit Analysis
Credit Card Distribution
Exit Rate by Products
Geography vs Exit Rate
Retention Rate Gauge
💡 Key Insights
Low-balance customers are more likely to churn
Inactive customers have higher churn rates
Certain regions show higher customer attrition
Customers with fewer products are at higher risk
🎯 Recommendations
Improve engagement for inactive users
Provide incentives for low-balance customers
Focus on high-churn regions
Promote cross-selling of products
🛠️ Tools & Technologies
Microsoft Power BI Desktop
DAX (Data Analysis Expressions)
Data Modeling (Star Schema)
📌 Conclusion

This project demonstrates how data analytics and visualization can help banks understand customer behavior and take data-driven actions to reduce churn and improve retention.
