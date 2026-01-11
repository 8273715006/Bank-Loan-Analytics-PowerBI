# Retail Lending Risk & Performance Analysis (Power BI)

## 📌 Project Overview

This is a **self-initiated Power BI analytics project** focused on analyzing retail bank loan data to evaluate lending performance, borrower risk, and repayment behavior. The project demonstrates end-to-end data analysis skills including data understanding, KPI creation, DAX measures, and interactive dashboard design.

The goal is to provide decision-makers with **clear, actionable insights** into loan portfolio health and risk patterns.

---

## 🧩 Business Problem

Financial institutions often face challenges in:

* Tracking overall loan performance
* Identifying high-risk borrower segments
* Monitoring funded vs recovered amounts
* Understanding default trends across grades, purposes, and geographies

This project addresses these challenges by building an interactive Power BI dashboard that highlights **key lending KPIs, risk indicators, and portfolio trends**.

---

## 📊 Dataset Description

* **Source**: Publicly available retail loan dataset
* **Format**: CSV
* **Records**: ~38,000 loan applications
* **Granularity**: Loan-level

### Key Columns:

* Loan Status (Fully Paid, Charged Off, Current)
* Funded Amount
* Received Amount
* Interest Rate
* Debt-to-Income Ratio (DTI)
* Loan Purpose
* Grade / Sub-grade
* State & Home Ownership
* Issue Date

> ⚠️ Data has been anonymized and is used strictly for learning and portfolio purposes.

---

## 🏗️ Data Modeling

* Single **Fact Table**: Loan transactions
* Date hierarchy derived from Issue Date
* Star-schema principles followed for performance
* Optimized for slicing by time, geography, loan purpose, and risk grade

---

## 📐 Key KPIs & Metrics

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average Debt-to-Income (DTI)
* Good vs Bad Loan Distribution
* Month-to-Date (MTD) & Month-over-Month (MoM) Trends

Custom DAX measures were created to calculate growth trends, portfolio risk ratios, and recovery insights.

---

## 📈 Dashboards Included

### 1️⃣ Executive Lending Snapshot

High-level KPIs to evaluate overall lending efficiency and portfolio health.

### 2️⃣ Portfolio Risk Analysis

Deep dive into:

* Loan distribution by grade, purpose, and tenure
* Geographic spread of loan applications
* Risk trends across borrower profiles

### 3️⃣ Loan-Level Transaction View

Detailed, filterable table to inspect individual loan records and repayment behavior.

---

## 🔍 Key Insights

* Majority of loans fall under **Good Loan category**, indicating stable portfolio quality
* Higher interest rates correlate with increased charge-off risk beyond certain grades
* Debt consolidation is the most common loan purpose
* Long-tenure loans contribute higher funded amounts but carry elevated risk

---

## 🛠️ Tools & Technologies

* **Power BI Desktop** – Data modeling & visualization
* **DAX** – Calculated measures & KPIs
* **CSV / Excel** – Source dataset

---

## 📂 Repository Structure

```
Bank-Loan-Analytics-PowerBI/
│
├── Dataset/
│   └── financial_loan.csv
│
├── PowerBI/
│   └── Retail_Lending_Analysis.pbix
│
├── Screenshots/
│   ├── executive_snapshot.png
│   ├── portfolio_risk.png
│   └── loan_details.png
│
└── README.md
```

---

## ⚠️ Disclaimer

This project is created solely for **educational and portfolio demonstration purposes**. It does not represent real banking data or business decisions.

---

⭐ If you find this project useful, feel free to explore the dashboards and share feedback.
