# Loan Risk Analysis Dashboard

## Overview
This project analyzes a loan portfolio to identify high-risk borrowers and understand the factors contributing to defaults. It demonstrates data cleaning, risk scoring, and visualization skills using Excel, making it ideal for a business-oriented data analyst portfolio.

The dashboard provides actionable insights into borrower risk levels, helping lenders make informed decisions.

---

## Dataset
The analysis uses the [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset) from Kaggle. 
Key columns include:

- Borrower information (age, employment length, income)  
- Loan details (loan amount, interest rate, loan grade)  
- Previous default status  
- Actual default outcome  

---

## Methodology
1. **Data Cleaning**  
   - Removed duplicates and blanks  
   - Corrected formatting, extra spaces, and typos  
   - Handled outliers and missing values using median and logical estimation  

2. **Risk Scoring**  
   A rule-based risk score was created using key factors:
   - Previous default (+3 points)  
   - Loan interest rate >15% (+2 points)  
   - Loan grade lower than D (E or worse) (+2 points)  
   - Employment length ≤2 years (+1 point)  

   Scores were categorized into Low, Medium, and High risk.

3. **Analysis & Pivot Tables**  
   Default rates were analyzed across:
   - Risk category  
   - Loan grade  
   - Employment length  
   - Interest rate  

4. **Dashboard & Visualization**  
   - Key KPIs: Total borrowers, Total defaults, Default rate, High-risk borrower count, Average loan amount, Average interest rate  
   - Charts: Default Rate by Risk Category, Loan Grade, Employment Length, Interest Rate, Portfolio Composition  

---

## Insights
- Borrowers with previous defaults are most likely to default again.  
- Loan grade and interest rate correlate strongly with default risk.  
- Shorter employment length is associated with higher defaults.  
- The Risk Score successfully segments borrowers into meaningful risk categories.

---

## Tools
- Microsoft Excel (Pivot Tables, Charts, Formulas)  
- No programming required; all analysis and dashboarding done in Excel

---
## Screenshots
<img width="1837" height="683" alt="image" src="https://github.com/user-attachments/assets/8f46f9f4-8078-4ca3-adfd-b92c40500ed5" />
<img width="1842" height="676" alt="image" src="https://github.com/user-attachments/assets/93df49c6-a91a-4dae-91f0-adaded17b384" />
<img width="1829" height="674" alt="image" src="https://github.com/user-attachments/assets/81c5e3cc-e533-4a4f-a2c9-3ea28b6dc866" />


---

## How to Use
1. Open `Loan_Risk_Dashboard.xlsx`  
2. View the KPI cards at the top for summary metrics  
3. Explore charts to understand risk distribution and factor impacts  
4. Use filters in pivot tables to analyze specific segments if needed

---

## Author
**Your Name** – Aspiring Data Analyst
