# Stock Analysis Project


# Quantitative Equity Analytics & Revenue Trend Pipeline

An automated data engineering and analysis pipeline built in Python to evaluate the correlation between corporate top-line revenues and macro market valuation shifts.

## Project Architecture & Milestones

* **Phase 1: Automated Asset Ingestion (API Pipeline)**
  Utilizes the `yfinance` API wrapper to extract deep historical time-series pricing data (`Open`, `High`, `Low`, `Close`, `Volume`) for volatile market equities (TSLA, GME).
  
* **Phase 2: Unstructured Fundamental Data Extraction (Web Scraping)**
  Deploys `requests` and `BeautifulSoup` to target and parse HTML fundamental data tables, using programmatic string normalization to clean financial float metrics.

* **Phase 3: Cointegrated Trend Visualization**
  Constructs a multi-axis data visualization pipeline to map corporate quarterly revenue timelines directly against historical pricing shifts to analyze valuation anchors.
