# Large Banking SQL Analysis

## Project Overview
This project demonstrates an end-to-end SQL and Python analysis of a simulated banking database.  
The goal is to explore customer activity, branch performance, transaction trends, and loan portfolios to extract actionable business insights.

## Tools & Technologies
- **SQLite**: Querying and aggregating the database  
- **Python (pandas, Matplotlib)**: Data analysis and visualization  
- **Jupyter Notebook**: Interactive workflow and documentation  
- **GitHub**: Project version control and portfolio showcase  

## Database
**LargeBankingDB.db** – a realistic simulated banking database.  

Tables used include:  
- `Branches`  
- `Customers`  
- `Accounts`  
- `Transactions`  
- `Loans`  

## Analyses & Insights

### Branch Account Overview
- **Question:** Average account balances per branch  
- **Insight:** Branches vary in average account balances, helping identify high-value branches and guide branch-level financial strategy.

### Customer Activity Overview
- **Question:** Top customers by transaction amount and frequency  
- **Insight:** Customers like Susan Estes dominate transaction totals. Frequency of transactions does not always correlate with total value, showing diverse customer behaviors.

### Top Customer Transaction Breakdown
- **Question:** Distribution of transaction types (Deposit, Withdrawal, Transfer) for top customers  
- **Insight:** Transfers contribute the most to total transaction amounts. Some customers show a balanced mix, but overall behavior varies, highlighting the need for personalized strategies.

### Branch Transaction Performance
- **Question:** Which branches handle the highest total transaction amounts?  
- **Insight:** Love, McDaniel and Hall handles the largest transaction value, while House-Reyes has the most transactions. Overall, activity is fairly balanced across branches.

### Transaction Trends Over Time
- **Question:** How does transaction activity change throughout the year?  
- **Insight:** May shows the highest transaction total, June the lowest. Clear monthly spikes suggest seasonal behavior such as salary cycles or periodic financial obligations.

### Loan Portfolio Overview
- **Question:** Most common loan types and total loan value  
- **Insight:** Car loans dominate both in number and total value. Home loans have the highest average loan amounts. The bank balances high-volume and high-value lending strategies.

### Customers with the Largest Loan Amounts
- **Question:** Which customers hold the largest total loan amounts?  
- **Insight:** Steven Lee holds the highest total loan amount with three loans. Top 10 customers’ loan totals are fairly close, highlighting a small group contributing significantly to the portfolio.

## Visualizations
All analyses are visualized with **Matplotlib**. Examples include:  
- **Bar plots:** Branch balances, top customers, loan types, top loan-holding customers  
- **Line plots:** Monthly transaction trends
