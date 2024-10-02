# News Articles Scraper and Analyzer

## Overview

This project was originally created for a class assignment to extract news articles and analyze their content. The goal is to map opinions expressed in articles, particularly for humanities students interested in opinion mapping.

## Project Structure

The project consists of two Jupyter notebooks:

1. **Install GeckoDriver Notebook**: This notebook guides you through the installation of GeckoDriver, which is required for running the web scraper.
2. **Run Program Notebook**: This notebook contains the main code for scraping Google News articles and analyzing their content.

### Important Notes

- This project is not suitable for large-scale scraping, as Selenium-based scraping can be slower and has not been tested with thousands of files.
- The scraping is focused solely on Google News.

## Features

- Extracts news articles from Google News.
- Analyzes the content for opinion mapping.

## Installation

### Dependencies

Make sure you have the following dependencies installed:

- **Python** (3.6 or higher)
- **pandas**: For data manipulation and analysis.
- **newspaper3k**: For extracting and parsing news articles.
- **selenium**: For web scraping.
- **webdriver_manager**: To automatically manage web drivers.

You can install the required libraries using pip:

```bash
pip install pandas newspaper3k selenium webdriver_manager
