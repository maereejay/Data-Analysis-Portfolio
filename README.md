# 📊 Data Analysis Portfolio

Welcome to my **Data Analysis Portfolio**. This repository contains projects I have completed to practice and demonstrate my data analysis skills across different tools and industries.  

The portfolio is organized by tool/technology:
Data-Analysis-Portfolio/
│
└── Excel/
└── Python/


Future folders will include **Python**, **SQL**, **Tableau**, and **Power BI** projects.  

---

## 🗂️ Excel Projects Highlights

### 1. ☕ Coffee Sales Analysis
**Objective:** Analyze coffee shop sales data to identify top-selling products, peak hours, and customer purchasing patterns to support inventory and marketing decisions.  

**Key Highlights:**
- Merged multiple CSV datasets and cleaned data for analysis.  
- Created PivotTables to identify top-selling coffee types and peak sales hours.  
- Built a **dashboard** summarizing insights on top products, peak periods, and daily sales patterns.  
- Delivered actionable recommendations for inventory management and marketing strategy.  


---

### 2. 🏦 Bank Marketing Campaign Analysis
**Objective:** Analyze a bank’s marketing campaign dataset to identify high-conversion customer segments and improve campaign targeting.  

**Key Highlights:**
- Segmented customers by age and education to identify high-conversion groups (age 68–77, tertiary education).  
- Evaluated campaign effectiveness by contact type and month, highlighting **cellular calls** and **December campaigns** as most effective.  
- Built a consolidated **Excel dashboard** summarizing insights for a marketing manager.  
- Delivered actionable recommendations for targeting and campaign strategy.  

---
### 3. Loan Risk Analysis Dashboard

**Objective:** Analyze a loan portfolio dataset to identify key drivers of borrower default and develop a risk segmentation framework for improved credit decision-making.

**Key Highlights:**
- Cleaned and prepared 30k+ loan records by handling missing values, outliers, and formatting inconsistencies.
- Developed a rule-based Risk Scoring Model using previous default history, loan grade, interest rate, and employment length.
- Segmented borrowers into Low, Medium, and High risk categories, achieving clear separation in default rates (High: 64%, Medium: 45%, Low: 16%).
- Evaluated impact of key factors (loan grade, employment length, interest rate, prior default) using pivot-based default rate analysis.
- Built a consolidated Excel dashboard with KPI cards and visualizations to support risk monitoring and lending decisions.
- Delivered actionable insights for credit risk assessment and portfolio management.

---
## 🗂️ Python Projects Highlights

### 1. Stroke Analysis Project

Performed data analysis on a dataset of 5,110 patients to identify factors associated with stroke.  

**Key Steps:**
- Cleaned and preprocessed data (handled missing values, duplicates, corrected data types)  
- Explored distributions of numeric (age, glucose) and categorical features (marital status, smoking, work type, hypertension, heart disease)  
- Visualized relationships with the target (stroke) using boxplots and bar charts  
- Conducted basic statistical analysis to identify impactful features  

**Insights:** Age, average glucose level, hypertension, and heart disease are strongly associated with stroke occurrence.  
Dataset and visualizations are ready for dashboarding in Tableau or Power BI.

---
### 2. NYC Taxi Trip Data Analysis

Analyze NYC taxi trips to identify *ride patterns, fare behavior, and passenger trends*.

**Key Highlights:**
- Cleaned 83,691 rows, handled missing and negative values, and extracted *hour, day, weekday, month, and trip duration*.  
- *Passenger analysis*: Most trips have 1 passenger; fares vary little by passenger count.  
- *Time-based patterns*: Peak ride hours at 3 PM, 5 PM, and 7 PM; lowest rides 2–4 AM.  
- *Trip distance vs fare*: Positive correlation; longer trips → higher fares, with a few outliers.  
- Visualizations and analysis performed with *Python, Pandas, Matplotlib, and Seaborn*.

---
## 🗂️ SQL Projects Highlights

### 1. Chinook Music Store SQL Analysis

Analyze the Chinook digital music store database to uncover insights about customer behavior, revenue trends, and product performance using SQL and Python.

**Highlights:**
- Identified **top-performing music genres and tracks** driving store revenue.
- Analyzed **customer distribution and purchasing behavior across countries**.
- Determined **top-spending and most frequent customers**.
- Explored **monthly revenue trends and seasonal purchase patterns**.
- Visualized key insights using Python to support data-driven storytelling.

**Tools Used:**
- **SQL (SQLite)** – Data extraction and aggregation
- **Python (Pandas)** – Data analysis
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis and documentation

---
### 2. Banking SQL Analysis

Analyze the LargeBankingDB simulated banking database to uncover insights about customer activity, branch performance, transaction trends, and loan portfolios using SQL and Python.

**Highlights:**

- Identified top-performing branches by account balances and transaction volumes.  
- Analyzed top customers by transaction activity and total transaction amounts.  
- Explored transaction type distributions for high-value customers.  
- Examined monthly transaction trends to uncover seasonal patterns.  
- Investigated the bank’s loan portfolio by loan type, total value, and average loan amounts.  
- Determined top customers by total loan amounts to highlight high-value clients.  
- Visualized all key insights to support data-driven business storytelling.  

**Tools Used:**

- **SQL (SQLite)** – Data extraction, aggregation, and joins  
- **Python (pandas)** – Data cleaning and analysis  
- **Matplotlib** – Visualization of trends, balances, and loan distributions  
- **Jupyter Notebook** – Interactive analysis and structured documentation

---
## 🗂️ Web Scraping Projects Highlights

### 1. 📚 Books Catalog Web Scraping
**Objective:** Scrape book data from [Books to Scrape](http://books.toscrape.com) and analyze price and rating trends to uncover patterns in the catalog.  

**Key Highlights:**
- Scraped **~1000 books** across 50 pages using `requests` and `BeautifulSoup`.  
- Extracted key fields: **title, price, and rating**.  
- Cleaned data: removed currency symbols and converted prices to numeric; mapped textual ratings (`One–Five`) to integers (1–5).  
- Conducted exploratory data analysis:  
  - **Price distribution:** most books cluster around £20, with a few expensive outliers.  
  - **Rating distribution:** majority of books have 1-star ratings; 2-star and 5-star books occur similarly, while 4-star books are least common.  
  - **Average price by rating:** prices are roughly consistent across ratings; 4-star books slightly higher on average.  
- Visualized findings using **histograms and bar charts** for clear communication of insights.  
- Documented the full workflow for **portfolio presentation**, highlighting scraping, cleaning, analysis, and visualization skills.  

**Insight Summary:**  
The catalog is dominated by affordable books (~£20) with mostly low ratings (1-star), and pricing shows minimal correlation with ratings, demonstrating data patterns that can inform further analysis or more complex scraping projects.

---
### 2. 💼 Remote Job Market Analysis (Web Scraping Project)
**Objective:** Scrape and analyze remote job listings to identify trends in job roles, skills demand, company hiring activity, and geographic distribution in the remote tech job market.

**Key Highlights:**
- Built a web scraping pipeline using **Python and Selenium** to collect job data from RemoteOK, extracting job title, company, location, posting time, and required skills.
- Cleaned and structured the scraped data using **Pandas**, handling duplicates, missing values, and inconsistent entries.
- Performed **exploratory data analysis and visualizations** to uncover the most demanded skills, common job roles, top hiring companies, and remote job location trends.
- Analyzed **job posting frequency** to understand how recently remote positions were published.
---
## 🔜 Upcoming Projects

- **Python Projects** → Analysis and web scraping.
- **SQL Projects** → Querying and joining datasets from relational databases.  
- **Tableau / Power BI Projects** → Interactive dashboards and visual storytelling.  

---

## ⚡ Notes
- All Excel projects follow a **structured workflow**: clean → explore → analyze → visualize → summarize insights.  
- Dashboards are designed for **stakeholder readability and actionable insights**.  
- As the portfolio grows, new folders will reflect the technology/tool used.  

---
