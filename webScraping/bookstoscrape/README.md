# Web Scraping Project: Books Catalog Analysis

## Project Overview
This project demonstrates web scraping, data cleaning, and exploratory data analysis (EDA) using Python. The goal was to extract information about books from the website [Books to Scrape](http://books.toscrape.com) and analyze patterns in **price** and **ratings**.

**Key objectives:**
- Scrape book data including **title, price, and rating**.
- Clean and structure the data for analysis.
- Perform EDA to uncover insights about pricing and ratings.
- Visualize findings for clear communication.

---

## Tools & Libraries
- Python 3.x  
- `requests` – for fetching webpage HTML  
- `BeautifulSoup` – for parsing HTML  
- `pandas` – for data manipulation and cleaning  
- `matplotlib` – for data visualization

---

## Data Collection & Workflow
1. **Website inspection**: Identified HTML structure for book elements:
   - Container: `<article class="product_pod">`
   - Title: `<h3><a title="...">`
   - Price: `<p class="price_color">`
   - Rating: `<p class="star-rating ...">`
2. **Fetch HTML** using `requests.get()`.
3. **Parse HTML** with BeautifulSoup to locate all book containers.
4. **Extract fields**: title, price, and rating for each book.
5. **Handle pagination** to scrape all 50 pages (~1000 books).

---

## Data Cleaning
- Removed unwanted symbols (`£` / encoding artifacts) from the **price** column and converted to float.  
- Converted **rating** from words (`One` → `Five`) to numeric values (1–5) for analysis.

---

## Exploratory Data Analysis (EDA) & Insights

### 1. Price Distribution
- Most books cluster around **£20**, with a few expensive books (£50–£60) increasing the overall average.  
- Insight: Majority of books are affordable, but outliers skew the mean price.

### 2. Rating Distribution
- Most books have a **1-star rating**.  
- 2-star and 5-star books occur at roughly the same frequency.  
- 4-star books are the least common.  
- Insight: The catalog contains a surprising number of low-rated books, with mid/high-rated books being less frequent.

### 3. Average Price by Rating
- Average price is roughly similar across ratings.  
- 4-star books are slightly more expensive, but the difference is minor.  
- Insight: Book rating does not strongly correlate with price in this catalog.

---

## Example Visualizations
- **Histogram** of book prices with average price line  
- **Bar chart** showing distribution of ratings  
- **Bar chart** showing average price by rating  

*(Include your plots from Matplotlib here as images in GitHub)*

---

## Conclusion
This project demonstrates the **complete web scraping workflow**:  
- Inspecting website structure → fetching HTML → parsing → extracting data → cleaning → analyzing → visualizing.  

It provides **basic insights** about book pricing and ratings, while also highlighting opportunities for more advanced analyses in future projects (e.g., category analysis, stock availability, price outliers).

---
