# Personal Finance & Investment Analytics Dashboard

## Project Overview
This project aims to analyze personal finance and investment data to better understand spending habits, optimize debt repayment, track investment performance, and plan for a FIRE (Financial Independence, Retire Early) lifestyle. The project consolidates historical spending data, credit card transactions, and investment information to produce actionable insights.

---

## Project Purpose
Managing personal finances effectively requires understanding spending habits and how they affect long-term savings and investment growth. Simply swiping a credit card doesn’t provide clarity, and relying on the next month’s paycheck to cover last month’s expenses can be risky. Inspired by *The Psychology of Money*, this project treats saving as “buying time for the future.”  

The goal is to visualize spending, identify debt drivers, track investments, and provide recommendations for improved financial health.

---

## Project Objectives
1. Maximize paying down debt each month and track progress toward being debt-free.  
2. Determine which spending categories contribute most to carry-over debt.  
3. Track investment performance and evaluate which ETFs are optimal for contributions.  
4. Plan and simulate a FIRE lifestyle based on current spending, savings, and investment patterns.  

---

## Data Sources
- Personal historical spending data (Excel/CSV files)  
- Credit card transaction history (CSV or exported Excel)  
- Optional public ETF performance datasets for investment tracking  

> **Note:** Sensitive data should be anonymized or replaced with sample datasets before sharing publicly.

---

## Tools & Technologies
- **Databricks** – Data cleaning, transformation, and modeling  
- **Python** – Analysis, calculations of metrics, and transformations  
- **SQL** – Querying and aggregating data for analysis  
- **Power BI** – Interactive dashboard for visualization of insights  
- **Star Schema Modeling** – Fact and dimension tables for analytical datasets  

---

## Project Workflow
1. Collect and consolidate all historical spending and investment data.  
2. Explore and clean the data, handling missing values, duplicates, and inconsistent categories.  
3. Design and implement a star schema (fact table: transactions/investments; dimension tables: time, category, account, investment).  
4. Compute key metrics and perform analysis using Python and SQL.  
5. Build an interactive Power BI dashboard to visualize spending, savings, and investment insights.  
6. Document findings, data dictionary, and actionable recommendations.

---

## Expected Deliverables
- Cleaned datasets ready for analysis  
- Data model diagram showing fact and dimension tables  
- SQL scripts for transformations and aggregations  
- Power BI dashboard with interactive visualizations  
- Documentation:  
  - Data dictionary (columns, meanings, data types)  
  - Summary of findings and insights  
  - Recommendations for improved spending and investing habits  
  - Screenshots of dashboards  

---

## Optional Future Enhancements
- Integration of real-time investment API data  
- Forecasting savings and portfolio growth under different scenarios  
- Automated monthly updates and dashboards  
- Data governance practices: naming conventions, refresh schedules, and quality checks
