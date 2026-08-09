# Customer Churn Analysis

A customer churn analysis project using Python, SQL, Excel, and Power BI to identify customer churn patterns, analyze high-risk customer segments, and understand factors affecting customer retention.

## Features

- Cleaned and prepared customer churn data
- Performed exploratory data analysis using Python
- Analyzed churn by contract type, tenure, internet service, and payment method
- Calculated overall and segment-level churn rates
- Used SQL for customer and revenue analysis
- Identified high-risk customer segments
- Estimated monthly revenue at risk
- Created a customer churn dashboard in Power BI
- Developed customer retention recommendations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Excel
- Power BI

## Analysis

The analysis focuses on understanding which customer groups are more likely to churn and the factors associated with customer attrition.

Key areas analyzed include:

- Contract type
- Customer tenure
- Monthly charges
- Internet service
- Payment method
- Customer risk segments

## Dashboard

The project includes a Power BI dashboard showing:

- Overall churn rate
- Churn by contract type
- Customer risk segments
- Churn by tenure
- Churn by internet service
- Churn by payment method

## Customer Risk Segmentation

Customers were classified into three risk groups using business rules based on contract type, tenure, monthly charges, and internet service.

- High Risk
- Medium Risk
- Low Risk

The segmentation can help identify customers who may require targeted retention campaigns.

## Business Recommendations

Based on the analysis, retention efforts can focus on:

- Customers on month-to-month contracts
- New customers with short tenure
- Customers with higher monthly charges
- Fiber optic customers showing higher churn risk
- Customers identified as high-risk

Possible actions include targeted offers, contract upgrades, personalized retention campaigns, and improved customer engagement.

## Project Files

- `churn_analysis.py` — Python analysis and SQL queries
- `churn_cleaned.csv` — Cleaned dataset with risk segments
- `customer churn dashboard.png` — Customer churn dashboard
- `Customer Churn Analysis Retention Strategy.docx` — Retention strategy document

## Dataset

The analysis uses the Telco Customer Churn dataset.
The original dataset contains customer information such as demographics, services, contract details, tenure, monthly charges, and churn status.
