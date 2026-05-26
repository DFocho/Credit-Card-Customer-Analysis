# 💳 Credit Card Customer Analytics & Churn Analysis (Power BI)

## 📌 Overview
This project analyzes customer behavior for a US-based credit card company to understand spending patterns, credit usage, payment behavior, and churn risk.
The goal is to identify:
- High-value customers
- Drivers of churn
- Revenue opportunities across customer segments and regions
________________________________________
## 📂 Dataset
The project uses a relational data model with multiple tables:
Core Tables
- customers.csv → Customer demographics & churn
- credit_accounts.csv → Credit limits, balances, account status
- transactions.csv → Spending behavior
- payments.csv → Repayment behavior
- usage_metrics.csv → Monthly aggregated usage
- regions.csv → State-to-region mapping
________________________________________
## 🔗 Data Model
- customers[customer_id] → all fact tables
- customers[state] → regions[state]
- credit_accounts[customer_id] → customers
This follows a star schema design with customers as the central dimension.
________________________________________
## 🎯 Objectives
- Analyze customer churn across segments and regions
- Understand spending behavior and revenue drivers
- Evaluate credit utilization and financial risk
- Identify high-value and high-risk customers
________________________________________
## 📊 Key KPIs & Metrics
### 💰 Revenue & Spend
- Total Spend
- Avg Spend per Customer
- Spend by Category
- Spend by Segment / Region
________________________________________
### 👤 Customer Metrics
- Total Customers
- Churn Rate
- Retention Rate
- Customers by Segment
________________________________________
### 💳 Credit Metrics
- Avg Credit Limit
- Avg Balance
- Utilization Rate
________________________________________
### 💸 Payment Metrics
- Total Payments
- Payment Rate (Payments / Balance)
- % Full vs Minimum Payments
________________________________________
### 🔁 Behavioral Metrics
- Transactions per Customer
- Avg Transaction Value
- Monthly Active Customers
________________________________________
## 📈 Key Analysis
### 1. Churn Analysis
- Churn by segment (Standard vs Platinum)
- Churn by region (West vs South, etc.)
________________________________________
### 2. Revenue Analysis
- Spend by category and segment
- High-value customers' contribution
- Regional revenue performance
________________________________________

### 3. Credit Risk Insights
- High utilization customers
- Low payment vs high balance users
- Segment-level risk patterns
________________________________________
## 💡 Insights
- Customers with high utilization (>80%) show higher churn risk
- Platinum customers generate the highest revenue but lowest churn
- Certain regions show higher churn despite strong spending
________________________________________
## 🚀 Business Recommendations
- Target high-risk customers with retention strategies
- Encourage higher payments to reduce credit risk
- Focus on high-value segments for revenue growth
- Personalize offers based on spending categories
________________________________________
## 🛠 Tools Used
- Power BI
- DAX (Data Analysis Expressions)
- Data modeling (star schema)
________________________________________
## 🧠 What I Learned
- Building a multi-table financial data model
- Creating advanced KPIs using DAX
- Creating interactive dashboard visuals 
- Analyzing customer lifecycle and credit behavior
- Translating data into business insights



