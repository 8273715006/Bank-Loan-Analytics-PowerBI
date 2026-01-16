# Retail Lending Risk & Performance Analysis (Power BI)

## Project Overview
This project is a self-initiated Power BI dashboard designed to analyze retail loan data with a focus on lending performance, borrower risk, and repayment behavior. The objective is to provide actionable insights that support data-driven lending decisions.

## Business Problem
Financial institutions need to continuously monitor loan portfolio health, identify high-risk segments, and understand default trends across time, geography, and borrower profiles. Traditional static reports often fail to provide this level of insight.

## Dataset
- Source: Public retail loan dataset
- Records: ~38,000 loan applications
- Granularity: Loan-level
- Time Period: 2021

## Data Modeling
- Fact table containing loan transactions
- Dynamic Date table for time intelligence
- Star schema principles applied
- Optimized for slicing by time, state, grade, and loan status

## Key KPIs
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)
- Good vs Bad Loan Distribution
- Month-to-Date (MTD) and Month-over-Month (MoM) Trends

## Dashboard Pages
### Executive Lending Snapshot
High-level KPIs summarizing overall lending performance and portfolio health.

### Portfolio Risk Analysis
Breakdown of loan applications by geography, tenure, employment length, purpose, and home ownership.

### Risk Insights & Observations
Focused risk analysis highlighting default behavior by credit grade, loan purpose, and time trends, supported by key business observations.

### Loan-Level Transaction View
Detailed transaction-level table allowing granular inspection of individual loan records.

## Key Insights
- Higher default risk is concentrated in lower credit grades (E–G)
- Debt consolidation loans contribute the largest share of charged-off funded amounts
- Bad loan trends indicate cyclical and seasonal risk patterns

## Tools & Technologies
- Power BI Desktop
- DAX
- CSV / Excel

## Disclaimer
This project is created solely for learning and portfolio demonstration purposes. The data used is anonymized and does not represent real financial decisions.
