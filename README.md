# flipkart-product-review-scraper
Flipkart Product Review Scraper
This Python script scrapes product reviews from Flipkart and saves them into a CSV file named after the searched product.

How it works:
Takes a product name as input.
Searches Flipkart for that product.
Opens the first result and extracts reviews (name, rating, heading, comment).
Saves all reviews in a CSV file.

Requirements:
Python 3
beautifulsoup4
requests

Install:
pip install beautifulsoup4 requests

Run:
python3 flipkart.py

Example output file:
oneplusnord.csv

Current issue:
The script gives "IndexError: list index out of range" because Flipkart changed its webpage structure.
Will work on it...

Note:
I created this project back in 2023 and now I’m pushing it to GitHub.
