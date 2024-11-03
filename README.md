# finance-webscraper

This project scrapes real-time S&P 500 index data from SlickCharts, extracting information about the top 500 publicly traded companies in the U.S. The data gathered includes rankings, company names, tickers, weights, prices, and other relevant information, which can be further used for data analysis and financial insights.

# Tech Stack

- Python: The primary language used for web scraping, data handling, and processing.
- Pandas: For organizing the scraped data in a structured format and performing data manipulation.
- BeautifulSoup4: A library to parse HTML content and extract specific elements from the web page.
- Requests: To handle HTTP requests and retrieve HTML data from the web.

# Features

- Data Extraction: Scrapes company information such as Company Name, Symbol, Weight, Price, Change and Percentage Change from the S&P 500 page on SlickCharts.
- Data Structuring: Organizes the extracted data into a pandas DataFrame, which can be easily exported to CSV or used in data analysis.
- Real-time Data: Retrieves up-to-date information on the S&P 500 as it appears on SlickCharts.

# Installation

```
pip3 install beautifulsoup4 pandas requests
```

After installation, you can run **main.ipynb**


