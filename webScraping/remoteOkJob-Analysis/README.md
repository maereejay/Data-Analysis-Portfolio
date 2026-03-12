# Remote Job Market Analysis (Web Scraping Project)

## Project Overview
This project uses web scraping and exploratory data analysis to examine trends in the remote tech job market. Job listings were scraped from the RemoteOK job board and analyzed to identify patterns in job roles, required skills, hiring companies, and geographic distribution.

The goal of this project is to demonstrate the complete data analysis workflow: **data collection → data cleaning → exploratory analysis → insights**, using Python and modern data analysis tools.

---

## Data Source
Data was collected from:

RemoteOK – https://remoteok.com

This site lists remote job opportunities from companies around the world and provides information such as job titles, company names, locations, required skills, and posting times.

---

## Tools & Technologies
- **Python**
- **Selenium** – for scraping dynamic website content
- **Pandas** – data cleaning and manipulation
- **Matplotlib** – data visualization
- **Collections (Counter)** – frequency analysis

---

## Data Collection (Web Scraping)
The dataset was created by scraping job listings directly from the RemoteOK website using Selenium.

The scraper collected the following fields for each job listing:

- Job Title
- Company
- Location
- Time Posted
- Skills / Tags

Selenium was used because RemoteOK loads job listings dynamically with JavaScript, which cannot be accessed using simple `requests` scraping.

---

## Data Cleaning
Several cleaning steps were performed after scraping:

- Removed duplicate job listings
- Handled missing values for job skills
- Filtered out placeholder or invalid entries
- Ensured all fields were properly structured in a Pandas DataFrame

The final dataset contains structured job listing data ready for analysis.

---

## Exploratory Data Analysis

### 1. Most Demanded Skills
Skills listed in job postings were extracted and analyzed to determine which technologies appear most frequently in remote tech roles.

A horizontal bar chart was used to visualize the **top demanded skills** across all job listings.

---

### 2. Job Title Distribution
Job titles were analyzed to understand the types of roles currently being advertised in the remote job market.

A frequency table was created to show how often each role appears in the dataset.

---

### 3. Company Hiring Activity
Companies were analyzed based on how many job postings they published.

This helps identify which companies are most actively hiring for remote roles.

---

### 4. Location Trends
Although these are remote jobs, many listings specify regions such as:

- Worldwide
- USA
- Europe

Location analysis highlights geographic trends in remote hiring.

---

### 5. Job Posting Frequency
The `time_posted` field was analyzed to understand how recently jobs were posted.

This provides insight into how active the remote job market is and how frequently new opportunities appear.

---

## Key Insights
Key observations from the analysis include:

- A wide variety of unique job titles, reflecting diverse hiring needs in the remote tech market.
- Several skills appear repeatedly across postings, indicating strong demand for certain technologies.
- Most companies post only a small number of roles, suggesting a distributed hiring landscape rather than dominance by a few large companies.
- Many listings are marked as **Worldwide or in United States**, highlighting the global nature of modern tech hiring.

---
