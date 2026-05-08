# yes-bank-business-analytics
Financial modelling and banking analytics project using Python, PostgreSQL, Pandas, SQL, and statistical analysis.
# Yes Bank Financial Modelling Project

## Overview
This project focuses on the financial modelling and business analytics of Yes Bank using Python, SQL, PostgreSQL, Pandas, and statistical analysis techniques. The project analyzes banking data to evaluate financial performance, growth trends, risk factors, and financial stability.

---

## Objectives
- Perform financial analysis of Yes Bank
- Analyze banking performance using financial ratios
- Apply statistical and econometric techniques
- Build financial models using Python
- Understand banking crisis and recovery patterns
- Generate business insights from financial data

---

## Technologies Used
- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Psycopg2
- Matplotlib
- Seaborn
- Statsmodels
- PyCharm

---

## Key Analysis Performed
- Financial Ratio Analysis
- Correlation Analysis
- Regression Modelling
- ANOVA Testing
- Data Cleaning & Preprocessing
- Statistical Analysis
- Data Visualization
- PostgreSQL Database Connectivity

---

## Financial Variables Analyzed
- Equity Capital
- Reserves
- Deposits
- Borrowings
- Investments
- Total Assets
- Total Liabilities
- Fixed Assets

---

## Financial Ratios Calculated
### Debt to Equity Ratio
Measures financial leverage and company risk.

### Asset Utilization Ratio
Evaluates efficiency of asset usage.

### Investment Ratio
Analyzes investment contribution to total assets.

---

## Features
- PostgreSQL Integration with Python
- Banking Data Analysis
- Financial KPI Evaluation
- Statistical & Econometric Modelling
- Data Visualization using Python
- Business Analytics Techniques

---

## Sample Python Code

```python
import psycopg2
import pandas as pd

conn = psycopg2.connect(
    host="localhost",
    port="5432",
    dbname="postgres",
    user="postgres",
    password="your_password"
)

df = pd.read_sql(
    "SELECT * FROM public.final_yesbank;",
    conn
)

print(df.head())

conn.close()
```

---

## Key Learning Outcomes
- Financial data preprocessing
- Banking sector analytics
- SQL and PostgreSQL integration
- Statistical analysis using Python
- Financial modelling concepts
- Data visualization techniques

---

## Project Conclusion
This project provided practical exposure to financial modelling, banking analytics, and statistical analysis using real-world financial data. The analysis helped in understanding financial performance, asset growth, risk structure, and financial stability of Yes Bank.

---

## Author
### Priyanshu Kumar Rao
