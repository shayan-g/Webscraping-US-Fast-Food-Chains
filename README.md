# Webscraping US Fast Food-Chains Data

## Overview

This project analyzes the geographic distribution and market impact of 9 major restaurant and coffee chains across the United States. The analysis combines web-scraped store location data with U.S. Census population data and stock market information to try and draw comparisons with one another.

## Questions the R Code Explores

- Are some chains more prevalent in certain states or regions despite having fewer stores overall?
- Which chains achieve the highest market penetration relative to local population?
- Can stock prices alone reflect store impact and store distribution patterns?

## Methodology

### Data Sources:

- Store locations scraped from Menuism.com using archived web pages (2021-2024)
- U.S. Census population data (2020) from Simple Wikipedia
- Stock prices from Yahoo Finance API using the yfR library (r library)

### Data Collection Process:

- Custom web scraping functions extract store counts by state for each chain
- Population data retrieved and cleaned to match state abbreviations
- Regional classifications applied (Northeast, South, Midwest, West)
- Financial data collected for publicly traded companies only
- All datasets joined on state identifiers for comprehensive analysis

### Viewing

- Download the HTML File to View it in your browser
- Open the PDF document within this repository and make sure to show all of the pages

## Technical Stack: 

- R with stringr, tibble, tidyverse, rvest for web scraping, yfR for financial data
