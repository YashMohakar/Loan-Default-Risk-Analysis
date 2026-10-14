# Loan-Default-Risk-Analysis
Created an interactive Power BI dashboard to analyze loan default risks using data from SQL and Excel/CSV files. The dashboard provides insights into loan approvals, credit risk, default rates, and branch performance to support better decision-making.


# Loan Default Risk Analytics


### Data Analytics Project | SQL • Power BI • Excel

An interactive analytics project exploring loan applications, approval trends, borrower credit risk, recorded defaults, and branch-level loan portfolio performance.

## 📌 1. Project Overview

Loan portfolio analysis helps financial institutions understand their lending activity, evaluate borrower segments, and monitor portfolio performance.

This project analyzes loan application data to explore approval patterns, risk classifications, credit scores, debt-to-income (DTI) ratios, employment categories, loan purposes, and branch performance.

Using SQL for data analysis and Power BI for visualization, the project transforms structured loan data into an interactive dashboard that makes portfolio trends easier to explore and communicate.

**Project type:** Descriptive Data Analytics  
**Domain:** Banking & Financial Services  
**Primary tools:** MySQL, Power BI, Microsoft Excel

## 🎯 2. Business Problem

Loan datasets contain information about applicants, loan amounts, approval decisions, and borrower risk characteristics. Analyzing these records manually can make it difficult to compare segments and communicate portfolio trends.

This project addresses the analytical challenge of organizing loan data into meaningful metrics and visualizations to help stakeholders:

- Understand loan application and approval patterns
- Examine borrower risk classifications
- Explore relationships between credit scores, DTI ratios, and risk categories
- Compare recorded default patterns across borrower segments
- Review loan distribution and performance across branches

The dashboard supports exploratory analysis and decision-making discussions. It is not an automated lending or default-prediction system.

## 🎯 3. Project Objectives

- Analyze total loan applications and approval outcomes
- Summarize the loan portfolio by amount and purpose
- Examine the distribution of High, Medium, and Low Risk categories
- Compare credit scores across risk categories
- Analyze DTI ratios across risk categories
- Investigate default patterns by employment type and loan purpose
- Compare loan amounts and approval patterns across branches
- Present key portfolio metrics in an interactive Power BI report

## 🛠️ 4. Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL | SQL queries, filtering, aggregation, and segment analysis |
| Microsoft Power BI | Interactive dashboards and data visualization |
| Microsoft Excel | Spreadsheet-based data handling |
| CSV | Structured source data |
| SQL | Business metric calculations and grouped analysis |

## 🔄 5. Analytical Workflow

The project follows a data analysis workflow:

1. **Data understanding:** Examine the loan dataset, available columns, and data structure.
2. **Data preparation:** Review data quality, missing values, data types, and consistency.
3. **SQL analysis:** Use filtering, aggregation, conditional logic, and grouping to explore loan metrics.
4. **Risk segmentation:** Compare borrower characteristics across risk categories and other relevant segments.
5. **Dashboard development:** Present summary metrics and analytical comparisons in Power BI.
6. **Validation:** Check that application counts, loan totals, approval figures, and default metrics agree across the source data, SQL results, and dashboard.
7. **Business interpretation:** Translate the analysis into observations that stakeholders can investigate further.

## 📊 6. Power BI Dashboard

The report is organized into three pages.

### Page 1 — Loan Default Risk & Financial Analytics

**Purpose:** Provide an overview of loan application activity and portfolio composition.

Includes:
- Total loan applications
- Approved applications
- Rejected applications
- Total loan amount
- Loan amount by purpose
- Applications by branch
- Risk category distribution
- Approval status breakdown

### Page 2 — Branch & Loan Portfolio Performance

**Purpose:** Compare loan portfolio characteristics and performance across branches.

Includes:
- Loan amount by branch
- Branch-level default rates
- Branch-wise approval status
- Loan portfolio distribution
- Loan amount by purpose

### Page 3 — Credit Risk & Default Analysis

**Purpose:** Explore borrower characteristics and recorded default patterns.

Includes:
- Risk category distribution
- Defaults by employment category
- Defaults by loan purpose
- Credit score versus risk category
- DTI ratio versus risk category

## 🖼️ 7. Dashboard Screenshots

### Loan Default Risk & Financial Analytics

![Loan Default Risk Dashboard](([https://github.com/YashMohakar/Loan-Default-Risk-Analysis/blob/main/PowerBI_screenshot_1%20(1).jpeg](https://github.com/YashMohakar/Loan-Default-Risk-Analysis/blob/main/PowerBI_screenshot_1%20(1).jpeg?raw=true)))

### Branch & Loan Portfolio Performance

![image alt]([Screenshots/PowerBI_screenshot_2.jpeg](https://github.com/YashMohakar/Loan-Default-Risk-Analysis/blob/main/PowerBI_screenshot_2.jpeg))

### Credit Risk & Default Analysis

![Credit Risk Dashboard]([Screenshots/PowerBI_screenshot_3.jpeg](https://github.com/YashMohakar/Loan-Default-Risk-Analysis/blob/main/PowerBI_screenshot_3.jpeg))

## 📈 8. Key Performance Indicators (KPIs)

The dashboard focuses on metrics that summarize loan activity and portfolio risk.

| KPI | Definition |
|---|---|
| Total Applications | Number of loan application records |
| Approved Applications | Number of applications marked as approved |
| Rejected Applications | Number of applications marked as rejected |
| Total Loan Amount | Sum of loan amounts in the selected population |
| Default Count | Number of records classified as defaults |
| Default Rate | Defaults divided by the defined eligible loan population |
| Risk Distribution | Application count or share within each risk category |

**Default rate calculation:**

Default rate (%) = (Number of defaults / Number of eligible loans) × 100

The denominator must be defined consistently. For example, a default rate among approved loans is different from a rate calculated across all application records.

## 🔍 9. Business Questions Answered

The analysis explores the following questions:

1. How are applications distributed between approved and rejected statuses?
2. How is the portfolio distributed across risk categories?
3. How do average credit scores vary across risk categories?
4. How do DTI ratios differ across risk categories?
5. How do recorded defaults vary by employment type?
6. How are loan amounts distributed across loan purposes?
7. How do loan amounts and approval patterns differ across branches?
8. Why should default rates be compared alongside default counts?
9. Which borrower segments may warrant further investigation?

These questions connect technical analysis with practical business use cases.

## 💡 10. Business Value

The project demonstrates how structured data analysis and visualization can help stakeholders:

- Monitor lending activity and approval outcomes
- Understand the composition of a loan portfolio
- Identify segments for further credit-risk investigation
- Compare branch-level portfolio characteristics
- Explore associations between borrower characteristics and risk categories
- Communicate analytical findings through a visual report

The findings should be interpreted alongside data quality, sample size, and metric definitions. Observed associations do not establish causation or guarantee future borrower outcomes.

## 🚀 11. How to Run the Project

### Prerequisites

- Microsoft Power BI Desktop
- MySQL and MySQL Workbench, if reproducing the SQL analysis
- Microsoft Excel or a compatible spreadsheet application

### Steps

1. Clone or download this repository.
2. Review the files in the `Datasets/` directory.
3. Import the source data into MySQL if you want to reproduce the SQL analysis.
4. Open `PowerBI/LOAN DATA FINAL.pbix` in Power BI Desktop.
5. If prompted, update the data source paths to match your local files.
6. Refresh the dataset and verify the displayed metrics.
7. Navigate through all three dashboard pages to explore the analysis.

## 📁 12. Repository Structure

```text
loan-default-risk-analysis/
│
├── Datasets/
│   ├── Loan_data.csv
│   └── Loan_Default_Risk_Analytics.xlsx
│
├── PowerBI/
│   └── LOAN DATA FINAL.pbix
│
├── Screenshots/
│   ├── PowerBI_screenshot_1.jpeg
│   ├── PowerBI_screenshot_2.jpeg
│   ├── PowerBI_screenshot_3.jpeg
│   ├── Approved_loans.png
│   ├── Default_loans.png
│   ├── Default_rate_among_approved_loans.png
│   ├── Risk_segment.png
│   ├── Risk_vs_Credit_Score.png
│   ├── Risk_vs_DTI.png
│   ├── Risk_vs_Employment.png
│   ├── Risk_vs_loan_Purpose.png
│   ├── Total_Application.png
│   └── Total_loan_amount.png
│
└── README.md
```

## 🔮 13. Future Improvements

Potential improvements include:

- Adding more interactive slicers and drill-through pages
- Strengthening data validation and reconciliation across all tools
- Standardizing default-rate calculations and documenting their denominators
- Adding time-based portfolio analysis if reliable date fields are available
- Investigating predictive modelling using suitable historical loan outcomes
- Evaluating any predictive model with appropriate validation metrics and safeguards against data leakage

## 📚 14. Key Learnings

This project provides practical experience with:

- SQL-based data analysis and aggregation
- Working with structured CSV and Excel data
- Comparing borrower and loan segments
- Designing multi-page Power BI dashboards
- Presenting KPIs and analytical comparisons
- Interpreting results while considering data quality and business context

## 👨‍💻 Project Summary

**Domain:** Banking & Financial Services  
**Project:** Loan Default Risk & Financial Analytics  
**Tools:** MySQL, Power BI, Microsoft Excel  
**Focus:** SQL Analysis, Credit Risk Exploration, Loan Portfolio Analysis, Data Visualization

---

*Note: This project is intended for analytical and educational purposes. Its findings should not be used as the sole basis for real-world lending decisions.*
