# 📊 Loan Portfolio Risk & Performance Analysis Using Excel

## 📌 Project Overview

This project analyzes a loan portfolio using **Microsoft Excel** to evaluate loan performance, credit-risk exposure, borrower characteristics, loan pricing, outstanding financial obligations, and portfolio trends.

The objective was to transform raw loan records into meaningful business insights that can support **credit-risk monitoring, portfolio management, underwriting review, recovery management, and data-driven lending decisions**.

The project uses:

- Data Cleaning
- Calculated Columns
- Excel Formulas
- PivotTables
- PivotCharts
- KPI Cards
- Slicers
- Dashboard Design
- Risk Segmentation
- Business Analysis

---

## 🎯 Business Problem

The financial institution manages a large loan portfolio but lacks sufficient visibility into the factors associated with poor loan performance and potential credit risk.

Without structured analysis, management may find it difficult to:

- Identify high-risk loan segments
- Monitor outstanding financial exposure
- Evaluate borrower affordability
- Understand loan-grade performance
- Assess loan pricing across credit grades
- Monitor portfolio growth and changing risk levels

This project addresses these challenges by analyzing historical loan data and presenting the findings through an interactive Excel dashboard.

---

## 🎯 Project Objectives

The main objective is to analyze the loan portfolio and provide data-driven insights into:

1. Overall loan portfolio performance
2. Performing, At Risk, and Adverse loans
3. Loan performance across credit grades
4. Outstanding principal exposure
5. Borrower debt-to-income categories
6. Interest-rate patterns across loan grades
7. Loan disbursement trends
8. Borrower characteristics associated with loan performance
9. Credit-risk monitoring
10. Management decision-making

---

## 📂 Dataset

The dataset used for this project is **LOAN_INFO** and contains **49,913 loan records**.

### Key Variables

| Variable | Description |
|---|---|
| Loan ID | Unique identifier for each loan |
| Client ID | Borrower/client identifier |
| Loan Amount | Amount initially borrowed |
| Terms | Loan duration |
| Interest Rate | Interest rate applied to the loan |
| Installment | Scheduled repayment amount |
| Loan Grade | Credit-risk grade |
| Loan Sub Grade | Detailed credit classification |
| Employment Title | Borrower's employment information |
| Employment Length | Length of employment |
| Home Owner | Home ownership status |
| Annual Income | Borrower's annual income |
| Verification Status | Borrower-information verification status |
| Disbursement Date | Date the loan was issued |
| Loan Status | Current loan performance status |
| Purpose | Purpose of the loan |
| Address State | Borrower's state |
| Debt Income Ratio | Borrower's debt-to-income ratio |
| Outstanding Principal Balance | Remaining unpaid principal |
| Total Payment | Total amount paid |
| Last Payment Date | Most recent payment date |
| Last Payment Amount | Most recent payment amount |
| Application Type | Type of loan application |

---

## 🧹 Data Cleaning & Preparation

Before analysis, the dataset was prepared using Microsoft Excel.

### Data preparation activities included:

- Checking for duplicate Loan IDs
- Checking missing values
- Replacing missing categorical values with `NA`
- Replacing missing numerical values with `0`
- Standardizing date formats
- Formatting numerical fields correctly
- Creating calculated fields for analysis
- Categorizing loan risk

No duplicate Loan IDs were found during the duplicate check.

---

## ⚠️ Risk Classification

To make the analysis easier to understand, loan statuses were grouped into three analytical categories:

### 🟢 Performing
Loans currently performing normally according to the defined classification.

### 🟡 At Risk
Loans showing a status that requires closer monitoring or early intervention.

### 🔴 Adverse
Loans with unfavorable outcomes requiring greater credit-risk or recovery attention.

---

## 📈 Key Portfolio KPIs

| KPI | Result |
|---|---:|
| Total Loans | 49,913 |
| Performing Loans | 42,671 |
| Adverse Loans | 6,963 |
| At-Risk Loans | 279 |
| Performing Rate | ~85.5% |
| Adverse Rate | ~14.0% |
| At-Risk Rate | ~0.6% |

### Portfolio Performance

Approximately **85.5%** of the analyzed loans are classified as Performing, while approximately **14.0%** are classified as Adverse and **0.6%** as At Risk.

The adverse segment therefore represents an important area for continued portfolio monitoring.

---

## 🔍 Key Business Insights

### 1. Overall Loan Performance

The portfolio contains 49,913 loans, with 42,671 classified as Performing.

Although most loans are performing, 6,963 loans are classified as Adverse.

**Business implication:**  
Management should continue monitoring adverse loans, particularly those with substantial outstanding principal balances.

---

### 2. Loan Grade Performance

Loan performance was analyzed across grades **A–G** using Performing, At Risk, and Adverse classifications.

The analysis identified **Grade C** as having the highest adverse proportion in the reported portfolio analysis.

**Business implication:**  
Loan grades should be monitored individually rather than relying only on overall portfolio performance.

---

### 3. Outstanding Principal Exposure

Outstanding principal was analyzed by loan grade to identify where financial exposure is concentrated.

The reported analysis shows the greatest adverse outstanding-principal exposure within **Grade C**, with approximately **₦90,000** associated with adverse loans.

**Business implication:**  
Risk management should consider both:

> **Risk Level + Outstanding Principal Balance**

rather than focusing only on the number of risky loans.

---

### 4. Debt-to-Income Ratio

Borrowers were grouped into three DTI categories:

| DTI Category | Portfolio Share |
|---|---:|
| High | 23.80% |
| Low | 27.57% |
| Medium | 48.63% |

The Medium DTI category represents the largest portion of the portfolio.

**Business implication:**  
Debt-to-income ratio should be incorporated into borrower affordability and credit-risk assessment.

---

### 5. Interest Rate & Loan Grade

Average interest rates were compared across loan grades.

| Loan Grade | Average Interest Rate |
|---|---:|
| A | 7.39% |
| B | 11.15% |
| C | 13.79% |
| D | 16.03% |
| E | 17.99% |
| F | 19.87% |
| G | 20.91% |

The analysis shows that average interest rates increase across the loan-grade scale, from approximately **7.39% for Grade A** to **20.91% for Grade G**.

**Business implication:**  
This analysis provides management with visibility into how loan pricing varies across credit grades and can support ongoing review of risk-based pricing.

---

### 6. Loan Disbursement Trends

Loan disbursement activity was analyzed across months using:

- Number of loans
- Total loan amount
- Outstanding principal balance

The analysis shows variation in lending activity throughout the year, with a noticeable increase toward the later months.

**Business implication:**  
Portfolio growth should be monitored together with adverse-loan rates and outstanding balances to identify whether risk is increasing alongside lending activity.

---

## 📊 Dashboard

The Excel dashboard provides a single-page overview of the loan portfolio.

### KPI Cards

- Total Loans
- Performing Loans
- Adverse Loans
- At-Risk Loans

### Dashboard Charts

- Loan Disbursement by Date
- Average Interest Rate by Loan Grade
- Outstanding Principal by Loan Grade
- Borrower Distribution by DTI Category
- Loan Grade Performance

### Interactive Filters

The dashboard includes slicers for:

- Home Ownership
- Loan Grade
- Verification Status

These filters allow management to move from a high-level portfolio view to detailed segment analysis.

---

## 🛠️ Tools & Techniques

### Software

**Microsoft Excel**

### Techniques Used

- Data Cleaning
- Data Validation
- Excel Formulas
- Calculated Columns
- PivotTables
- PivotCharts
- KPI Cards
- Slicers
- Dashboard Design
- Descriptive Analysis
- Risk Segmentation
- Business Interpretation

---

## 💼 Business Recommendations

Based on the analysis, the following actions are recommended:

### 1. Strengthen Early-Warning Monitoring
Monitor At-Risk loans proactively so that intervention can occur before loans deteriorate into more serious adverse outcomes.

### 2. Prioritize High-Exposure Risky Loans
Combine risk classification with outstanding principal when prioritizing monitoring and recovery activities.

### 3. Monitor Loan-Grade Performance
Regularly evaluate adverse rates across loan grades to identify segments requiring additional review.

### 4. Strengthen Affordability Analysis
Use DTI as part of borrower affordability assessment, particularly where historical evidence supports an association with adverse outcomes.

### 5. Review Risk-Based Pricing
Compare interest rates, loan grades, and observed performance to support appropriate pricing decisions.

### 6. Monitor Portfolio Growth
Track loan disbursement growth alongside adverse rates and outstanding balances.

### 7. Improve Data-Driven Decision Making
Use dashboards and periodic portfolio reporting to identify emerging trends and support management decisions.

---

## 📌 Business Value

This project demonstrates how Excel can be used to transform raw financial data into actionable business intelligence.

The analysis can support:

- **Credit Risk Management** — identify loan segments requiring closer monitoring
- **Portfolio Management** — monitor loan volume, performance, and exposure
- **Underwriting** — incorporate borrower income and DTI into affordability analysis
- **Recovery Management** — prioritize adverse loans based on outstanding principal
- **Management Reporting** — provide decision-makers with an interactive portfolio overview

---

## 📁 Project Structure

```text
Loan-Portfolio-Risk-Analysis/
│
├── README.md
├── LOAN_INFO.xlsx
├── Loan_Portfolio_Risk_Analysis.xlsx
└── Dashboard/
    └── Loan_Portfolio_Dashboard.png
