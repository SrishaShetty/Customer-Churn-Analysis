# Customer Churn Analysis

Customer churn analysis project using Python and SQL to understand customer churn patterns, identify high-risk customers, and find factors that may affect customer retention.

## Features

- Data cleaning and preparation
- Exploratory data analysis
- Churn rate analysis
- Churn analysis by contract type
- Churn analysis by customer tenure
- Churn analysis by monthly charges
- Churn analysis by internet service
- Churn analysis by payment method
- Customer risk segmentation
- SQL-based customer analysis
- Revenue-at-risk analysis
- Export of cleaned customer data

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Jupyter Notebook

## Analysis

The project analyzes customer data to understand customer churn patterns and identify customer groups that may be more likely to leave a telecom service.

The analysis focuses on:

- Overall churn rate
- Contract type
- Customer tenure
- Monthly charges
- Internet service
- Payment method
- Senior citizen status
- Customer risk segments

## Customer Risk Segmentation

Customers were classified into three risk groups using business rules based on contract type, tenure, monthly charges, and internet service.

- High Risk
- Medium Risk
- Low Risk

This segmentation helps identify customers who may require targeted retention efforts.

## SQL Analysis

SQL queries were used to analyze:

- Overall churn rate
- Churn by contract type
- High-risk customers
- Revenue at risk
- Churn by customer type

SQLite was used to create and analyze the customer database.

## Key Business Insights

The analysis helps identify customer groups with higher churn risk, particularly customers with shorter tenure and month-to-month contracts.

The results can be used to support customer retention strategies such as targeted offers, contract upgrades, and personalized retention campaigns.

## Project Files

- `churn_analysis.ipynb` — Complete Python, EDA, and SQL analysis
- `churn_cleaned.csv` — Cleaned customer dataset with risk segments
- `README.md` — Project documentation

## Dataset

The dataset used in this project is the **Telco Customer Churn dataset**, available on Kaggle. Search for **"Telco Customer Churn"** on Kaggle.

The raw dataset is not included in this repository.
