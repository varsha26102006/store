# E-commerce Book Data Analysis

## Business Problem
Analyzed online book listing data to understand pricing patterns and 
customer rating trends, similar to how a retail analyst would study 
product performance.

## Data Source
Scraped 100 book listings (title, price, rating, availability) from 
books.toscrape.com using Python (Requests + BeautifulSoup).

## Data Cleaning
- Removed currency symbols and converted price to numeric
- Converted text-based ratings ("Three") into numeric values (3)
- Checked and removed duplicate entries
- Verified no missing values remained

## Key Findings
- Average book price: £[YOUR NUMBER HERE]
- [Fill in: did price go up or down with rating? or stay flat?]
- Most books were in stock (or whatever you found)
- [Fill in: what did the price distribution chart look like — mostly cheap books? evenly spread?]

## Tools Used
Python, Pandas, SQLite (SQL), Matplotlib

## Files in this project
- `01_scraping_and_cleaning.ipynb` — scraping and cleaning code
- `raw_ecommerce_data.csv` — raw scraped data
- `cleaned_ecommerce_data.csv` — cleaned data
- Charts included in notebook