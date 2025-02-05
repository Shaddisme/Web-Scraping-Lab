# Web Scraping Lab

## Overview
This project demonstrates how to scrape data from a webpage using Python and libraries like `requests`, `BeautifulSoup`, and `pandas`. The scraped data includes **programming languages** and their **average annual salaries**, which is then saved into a CSV file.

## Steps Performed
1. **Import Libraries**: Loaded necessary Python libraries (`requests`, `BeautifulSoup`, and `pandas`).
2. **Download Webpage**: Retrieved HTML content from the provided URL.
3. **Parse HTML**: Used BeautifulSoup to parse and extract specific data from the webpage.
4. **Extract Data**: Scraped programming language names and their corresponding average salaries.
5. **Save to CSV**: Saved the scraped data into a file named `popular-languages.csv`.

## Files
- **`popular-languages.csv`**: Contains the scraped data in a tabular format with two columns:
  - `Programming Language`
  - `Average Annual Salary`

## How to Run
1. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
   ```
2. Run the Python notebook or script provided.
3. The output file, `popular-languages.csv`, will be generated in the same directory.

