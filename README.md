# Webscraping_project
This project automates the extraction of financial data for various Indian industry sectors using web scraping techniques. By scraping structured HTML tables from [Screener.in](https://www.screener.in), we compile sector-wise financial comparisons into pandas DataFrames for further analysis or export.

---

## 🎯 Objective

- Scrape tabular financial data for various industry sectors like:
  - Agro Chemicals
  - Banks
  - Cement
  - IT Software
  - Power & Energy
- Structure the data into DataFrames for analysis or export

---

## 🛠️ Tools & Libraries

- Python
- `requests` – Sending HTTP requests
- `BeautifulSoup` – Parsing HTML content
- `pandas` – Storing and structuring scraped data
- `re`, `warnings`, `time` – Utilities for text cleaning and rate-limiting

---

## 🔍 How It Works

1. **Access each sector's Screener.in comparison page**
2. **Extract the HTML table** using BeautifulSoup
3. **Clean and parse rows** into a structured format
4. **Store in a DataFrame** for later analysis or export

---


## 🚀 Future Improvements

- Add pagination support to scrape all entries
- Enable input for custom sector scraping
- Store results in a database or `.csv` exports
- Create a dashboard for visualizing financial metrics

---

## 👨‍💻 Author

**Phanidhar Venkata Naga Kasuba**  
MS in Data Analytics, Webster University  
📫 Email: pkasubavenkatana@webster.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/YOUR_USERNAME) *(insert your LinkedIn link)*

---
