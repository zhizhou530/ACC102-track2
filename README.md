# WRDS Stock Risk and Return Analysis
## 1. Problem & User
This project analyzes the risk–return trade-off of selected stocks using WRDS data. It is designed for beginner investors who want to understand how volatility and return differ across stocks.
## 2. Data 
Source: WRDS CRSP Monthly Stock File

Access date: 2026-4-20

Key fields: date, permno, ret
## 3. Methods
SQL query via WRDS to extract stock return data

Data cleaning (handling missing values, formatting dates)

Transformation (pivot table, return alignment)

Descriptive statistics

Visualization (cumulative returns, correlation heatmap)

Risk analysis (annual return, volatility, Sharpe ratio)
## 4. Key Findings 
TSLA shows the highest average return but also the highest volatility

AAPL and MSFT provide more stable and consistent performance

Strong correlation exists between AAPL and MSFT

Diversification across stocks reduces overall investment risk
## 5. How to run
1.Install dependencies:pip install wrds pandas matplotlib seaborn

2.Run the Python script:python stock_analysis.py

3.Make sure you have a valid WRDS account for database access
## 6. Product link
[acc102.ipynb](https://github.com/zhizhou530/ACC102-track2/blob/main/acc102.ipynb)
## 7. Limitations & next steps
The analysis uses only three stocks, which limits generalizability

Monthly data may overlook short-term volatility

No macroeconomic or factor models are included

Future improvements:

Add more stocks for portfolio analysis

Apply CAPM or Fama-French models

Build an interactive dashboard (e.g., Streamlit)
