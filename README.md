# Quantitative Equity Analytics & Revenue Trend Pipeline

An automated data engineering and comparative financial analysis pipeline built in Python to evaluate the correlation between corporate top-line quarterly revenues and historical macro valuation shifts.

## Project Structure & Data Pipeline Milestones

* **01_TSLA_Market_Data_Extraction.ipynb**
  Establishes an automated asset data extraction pipeline using the `yfinance` API wrapper to capture deep historical time-series pricing channels (`Open`, `High`, `Low`, `Close`, `Volume`) for Tesla, Inc.
  
* **02_TSLA_Revenue_Web_Scraping.ipynb**
  Deploys programmatic HTTP requests via `requests` and parses unstructured data tables using `BeautifulSoup` to extract Tesla's quarterly financial histories, normalizing string values into algorithmic float types fit for modeling.

* **03_GME_Market_Data_Extraction.ipynb**
  Replicates the systematic API asset data ingestion framework to pull historical daily time-series pricing logs for GameStop Corp.

* **04_GME_Revenue_Web_Scraping.ipynb**
  Deploys web scraping and textual data-cleansing pipelines to systematically capture and isolate historical quarterly top-line revenue for GameStop.

* **05_Cointegrated_Trend_Visualization.ipynb**
  The central analytical layer of the pipeline. Designs a custom, dual-axis visual diagnostic dashboard layout using `Matplotlib` to directly map corporate fundamental revenue growth timelines against granular stock price movements over identical historical windows.

## Core Technologies & Libraries Used
* **Data Ingestion:** `yfinance` API, `requests` HTTP Library
* **Data Processing & ETL:** `pandas` (DataFrames, text parsing, cleanup string operations, data normalization)
* **Web Scraping:** `BeautifulSoup` (HTML table parsing)
* **Data Visualization:** `matplotlib` (Subplots, dual-axis multi-metric trends)
