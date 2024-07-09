# Job Scraper for Wuzzuf.net

This project is a Python-based web scraper designed to collect job listings from [Wuzzuf.net](https://wuzzuf.net/). The scraper extracts various job details such as job heading, status, company name, address, description, and job link, and compiles the data into a pandas DataFrame for further analysis or export.

## Features

- Retrieves job listings based on a query.
- Collects detailed information for each job listing.
- Limits scraping to the first 7 pages to avoid excessive load on the website.
- Stores the collected data in a pandas DataFrame.

## Requirements

- Python 3.x
- Requests
- BeautifulSoup4
- Pandas
## Main function that orchestrates the scraping process:

- Constructs the initial URL.
- Fetches and parses the HTML content.
- Calculates the number of pages to scrape (up to a maximum of 7 pages).
- Iterates through the pages and collects job data.
- Compiles the collected data into a pandas DataFrame and returns it.
