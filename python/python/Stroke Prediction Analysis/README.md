# Stroke Analysis Project

## Overview
This project explores a dataset of 5,110 patients to identify factors associated with stroke.  
The goal is to perform a structured **data analyst workflow**, from cleaning and exploration to insights, preparing the dataset for visualization and reporting.

---

## Dataset
- **Rows:** 5,110  
- **Columns:** 12 (original)  
- **Target Column:** `stroke` (Yes/No)  

**Selected Features for Analysis:**

### Numeric
- `age`  
- `avg_glucose_level`  

### Categorical / Binary
- `ever_married`  
- `smoking_status`  
- `work_type`  
- `hypertension` (0 → No, 1 → Yes)  
- `heart_disease` (0 → No, 1 → Yes)  

---

## Project Workflow

1. **Data Cleaning**
    - Handled missing values and duplicates  
    - Corrected data types and labels for clarity (0/1 → Yes/No)  
    - Dropped irrelevant or inconsistent rows (e.g., age < 1 month)  

2. **Exploratory Data Analysis (EDA)**
    - **Univariate Analysis:** Distribution of numeric and categorical features  
    - **Target Distribution:** Stroke occurrence (Yes/No)  
    - **Visualizations:** Boxplots for numeric features, bar plots for categorical features  

3. **Bivariate Analysis**
    - **Numeric vs Stroke:** Mean differences to identify impactful features  
    - **Categorical vs Stroke:** Chi-square tests and percentage-based bar plots  

4. **Insights**
    - Age and average glucose level are strongly associated with stroke  
    - Hypertension, heart disease, marital status, smoking status, and work type show meaningful differences  
    - Binary features encoded as Yes/No for clarity  

---

## Tools & Libraries
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## Output
- Cleaned dataset ready for visualization and dashboarding  
- Visualizations for both numeric and categorical features  
- Statistical analysis results identifying impactful features  

---

## Next Steps
- Build interactive dashboards in **Tableau** or **Power BI**  
- Summarize actionable insights for stakeholders  
- Optionally, extend analysis to predictive modeling  

---

