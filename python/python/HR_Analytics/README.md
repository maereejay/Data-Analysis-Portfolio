# 📊 Employee Attrition Analysis

## 📌 Project Overview

This project analyzes employee attrition using Python to identify key factors influencing employee turnover.

The objectives were to:

- Clean and explore HR data
- Identify high-impact drivers of attrition
- Quantitatively measure feature impact
- Prepare insights for dashboard development (Power BI)

---

## 📂 Dataset

The dataset contains HR employee records including:

- Demographics (Age, MaritalStatus)
- Job-related information (JobRole, BusinessTravel, OverTime)
- Satisfaction metrics (JobSatisfaction, EnvironmentSatisfaction)
- Experience metrics (YearsAtCompany, TotalWorkingYears, YearsWithCurrentManager)
- Target variable: **Attrition (Yes/No)**

---

## 🔎 Analysis Process

### 1️⃣ Data Cleaning

- Verified data types (categorical vs numeric)
- Checked for missing values
- Confirmed target variable structure
- Created binned versions of selected numeric features

---

### 2️⃣ Feature Impact Analysis

#### Categorical Features

Attrition rate was calculated using:

- OverTime
- JobRole
- MaritalStatus
- BusinessTravel

Method:
- Grouped by feature
- Calculated normalized attrition rate (% Yes)

---

#### Numeric Features

Selected numeric features:

- Age
- DailyRate
- EnvironmentSatisfaction
- JobSatisfaction
- JobInvolvement
- PerformanceRating
- TotalWorkingYears
- YearsWithCurrentManager
- YearsInCurrentRole

Approach:
- Applied binning (manual and quantile-based)
- Calculated attrition rate per bin
- Compared highest vs lowest risk ranges

---

### 3️⃣ Visualization

- Bar charts of attrition rate by feature
- Identified strongest drivers
- Selected high-impact variables for dashboard design

---

## 📈 Key Insights

- Employees working overtime showed significantly higher attrition.
- Employees with fewer years at the company had higher turnover rates.
- Certain job roles demonstrated elevated attrition risk.
- Satisfaction variables showed moderate impact.
- Performance rating showed minimal influence on attrition.

---

## 🛠 Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository  
2. Install dependencies:

```bash
pip install pandas matplotlib
