# Paytm FinTech Business Intelligence Dashboard

Project Overview

This project is a SQL-driven Power BI dashboard built for a Paytm-like FinTech company.

The main goal of this project is to help the business shift from volume-driven growth to sustainable and profitable growth by analyzing:
	•	Transactions
	•	Revenue
	•	Cashback impact
	•	Merchant performance
	•	Loan risk
	•	Fraud patterns
	•	User retention

All business logic and KPI calculations were handled in MySQL, and Power BI was used for interactive visualization.

⸻

Business Problem

The company processes a large number of digital transactions but faces challenges such as:
	•	Cashback and refund leakage
	•	High overdue loan percentage
	•	Transaction failures
	•	Revenue concentration among a few merchants
	•	User drop-off after onboarding
	•	Increasing operational and credit risk

Leadership needed a clear and interactive dashboard to understand where revenue is coming from and where risks are building.

⸻

Project Objectives
	•	Identify profitable vs non-profitable segments
	•	Measure cashback impact on net revenue
	•	Monitor transaction success and failure trends
	•	Evaluate merchant contribution and concentration
	•	Analyze loan overdue risk
	•	Track user retention through cohort analysis
	•	Provide one clear view of business health

⸻

Dataset Overview

The dataset includes:
	•	20,000+ Users
	•	100,000+ Transactions
	•	5,000+ Merchants
	•	8,000+ Loans
	•	1,300+ Fraud Cases
	•	Multi-year transaction history

The data covers:
	•	GMV and revenue
	•	Cashback and refunds
	•	Loan disbursement and overdue amounts
	•	Fraud flags
	•	Merchant categories
	•	User KYC status
	•	Retention cohorts

⸻

Tools Used
	•	MySQL Workbench
	•	SQL
	•	Power BI
	•	Data Modeling
	•	Cohort Analysis

⸻

Methodology

Data Preparation
	•	Raw data stored in MySQL
	•	SQL queries used to calculate KPIs
	•	Business rules applied for active users, fraud rate, overdue percentage, and retention
	•	Aggregations performed at monthly and category levels

Visualization
	•	Power BI connected directly to MySQL
	•	Interactive filters enabled
	•	Multiple dashboard pages created
	•	Clean and business-focused layout

All KPI logic was handled in SQL to ensure consistent and reliable results.

⸻

Dashboard Pages

Executive Overview
	•	Total GMV
	•	Total Transactions
	•	Transaction Success Rate
	•	Net Revenue
	•	Active Users
	•	Active Merchants
	•	Overdue Loan Percentage
	•	Failed Transactions

This page provides a quick summary of overall business health.

⸻

Transaction Analysis
	•	Successful vs Failed Transactions
	•	Failure Reasons
	•	Monthly Trends
	•	Payment Mode Comparison

This page helps identify operational issues and performance patterns.

⸻

User and KYC Analysis
	•	Active Users
	•	New Users
	•	Transactions per User
	•	GMV by KYC Status

This page helps understand engagement levels and compliance impact.

⸻

Merchant Performance
	•	GMV per Merchant
	•	Top Merchant Contribution Percentage
	•	Category-wise Revenue
	•	Merchant Ranking

This page identifies monetization opportunities and revenue concentration risk.

⸻

Cashback and Refund Analysis
	•	Total Cashback
	•	Refund Amount
	•	Net Revenue After Incentives
	•	Cashback Percentage of GMV

This page helps detect revenue leakage.

⸻

Loan and Risk Analysis
	•	Total Loan Amount
	•	Overdue Loan Percentage
	•	Average Days Past Due
	•	Loan Status Distribution

This page monitors credit stress and risk exposure.

⸻

Retention and Cohort Analysis
	•	Overall Retention Percentage
	•	Month 1 vs Month 6 Retention
	•	Cohort Heatmap
	•	Retention Funnel

This page helps detect user drop-off patterns over time.

⸻

Key Insights
	•	High overdue percentage indicates credit risk pressure
	•	Cashback and refunds significantly reduce net revenue
	•	Revenue is concentrated among top merchants
	•	Retention drops after the initial onboarding period
	•	Transaction failures are driven by recurring technical reasons

⸻

Business Recommendations
	•	Reduce cashback for low-value users
	•	Strengthen fraud monitoring for suspicious patterns
	•	Focus retention campaigns within the first three months
	•	Improve merchant cross-sell strategy
	•	Monitor overdue loans more closely

⸻

How to Run This Project
	•	Import the dataset into MySQL
	•	Execute SQL queries or views
	•	Connect Power BI to MySQL
	•	Load prepared SQL datasets
	•	Open the .pbix file
	•	Explore the interactive dashboard

⸻

Why This Project Matters

This project demonstrates how a FinTech company can move from transaction growth to sustainable revenue growth using structured data analysis.

It reflects real-world challenges in:
	•	Digital payments
	•	Merchant monetization
	•	Loan risk management
	•	Incentive control
	•	Customer retention


