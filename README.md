Wuzzuf Data Engineer Jobs ETL Pipeline
Overview

This project is a simple ETL pipeline built with Python to scrape, clean, and structure Data Engineer job listings from Wuzzuf. It demonstrates practical data engineering fundamentals including web scraping, data transformation, and dataset preparation.

Features
Scrapes job listings using Requests and BeautifulSoup
Handles pagination automatically
Extracts structured fields (title, company, location, job type, experience, posting date)
Converts relative posting dates into actual dates
Cleans data and removes duplicates
Exports final dataset to CSV
Tech Stack
Python
BeautifulSoup
Requests
Pandas
CSV
Pipeline Workflow
Extract job listings from Wuzzuf search pages
Parse and structure relevant job fields
Transform posting dates into standardized format
Clean dataset (handle missing values, remove duplicates)
Load final dataset into a CSV file
Output
Raw.csv: Unprocessed scraped data
cleaned.csv: Cleaned and structured dataset ready for analysis
Note

This project is implemented in a Jupyter Notebook (.ipynb). Make sure to run all cells in order to properly execute the scraping and data processing pipeline.

Purpose

This project simulates a basic real-world ETL workflow used in data engineering pipelines for collecting and preparing job market data for analysis or further processing.
