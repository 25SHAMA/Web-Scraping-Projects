# Quotes Web Scraper

This project scrapes quotes from [Quotes to Scrape](https://quotes.toscrape.com/) using **Python, BeautifulSoup, and Requests**.  
The data includes each quote, its author, unique author ID, tags, and a link to the author’s page. Results are saved into a CSV file.

## 🔎 Data Scraped
- Quote text
- Author name
- Author ID (unique identifier parsed from the site)
- Tags (multiple per quote)
- Author profile link

## 📂 Files
- `Quotes_Web_Scraper.ipynb` → Jupyter Notebook with scraping code  
- `Quotes.csv` → Output dataset (quotes, author info, tags)

## ▶️ How to Run
1. Open `Quotes_Web_Scraper.ipynb`.  
2. Run all cells.  
3. The scraper will collect quotes and save them into `Quotes.csv`.  

## 📊 Output Example
| Quote                                   | Author          | Author_ID | Tags                     | Author_Link                          |
|-----------------------------------------|-----------------|-----------|--------------------------|---------------------------------------|
| “The world as we have created it ...”   | Albert Einstein | 1         | change, deep-thoughts... | https://quotes.toscrape.com/author/...|
| “It is our choices, Harry, that show...”| J.K. Rowling    | 2         | inspirational, choices   | https://quotes.toscrape.com/author/...|

---

