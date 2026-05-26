# Project Description

## Aamazon web scrapping

Amazon product web scraping project built with Python, BeautifulSoup, Requests, and CSV export functionality.

---

# README.md

# Amazon Product Web Scraper

A simple Python web scraping project that extracts product information from Amazon product pages using BeautifulSoup and Requests.

## Features

* Extracts product title
* Extracts product price
* Extracts product description/about section
* Extracts customer review summary
* Saves scraped data into a CSV file
* Uses BeautifulSoup for HTML parsing

## Technologies Used

* Python
* BeautifulSoup4
* Requests
* CSV
* lxml parser

## Project Structure

```bash
web-scraping-project/
│
├── web scraping.ipynb
├── requirements.txt
├── README.md
└── output.csv
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/web-scraping-project.git
```

Move into the project folder:

```bash
cd web-scraping-project
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
web scraping.ipynb
```

The scraper extracts:

* Product Name
* Product Price
* Product Description
* Customer Reviews
* Ratings

Then saves the output into a CSV file.

## Example Output

| Product Name  | Price | Rating | Description                   |
| ------------- | ----- | ------ | ----------------------------- |
| Apple AirPods | 24999 | 4.5    | Noise cancellation headphones |

## Important Notes

* Amazon may block requests if too many requests are sent.
* Use headers/user-agent while making requests.
* Scraping Amazon may violate their Terms of Service.
* This project is for educational purposes only.

## Future Improvements

* Add multiple product scraping
* Add proxy rotation
* Add pagination support
* Export to Excel/JSON
* Build a GUI or web app
* Add error handling and logging

## Author

Shardul Nautiyal

---

# requirements.txt

```txt
beautifulsoup4
requests
lxml
jupyter
```

---

# Suggested GitHub Repository Name

* amazon-product-web-scraper
* python-web-scraping-project
* amazon-scraper-bs4
* web-scraping-with-python

---

# Suggested .gitignore

```gitignore
__pycache__/
*.pyc
.ipynb_checkpoints/
output.csv
.env
```
