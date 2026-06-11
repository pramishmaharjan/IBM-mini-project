# Historical Stock Data Visualization and Analysis

An end-to-end data analysis project extracting, cleaning, and visualizing historical stock data for **Tesla (TSLA)** and **GameStop (GME)** using the yfinance API and web scraping.

## Overview

This project demonstrates a complete data analysis pipeline:
- **Data Extraction**: Pull historical stock prices via the `yfinance` API and scrape quarterly revenue data from MacroTrends using BeautifulSoup
- **Data Cleaning**: Parse and clean revenue tables, handle missing values, and normalize formats
- **Visualization**: Generate interactive Plotly charts showing share price vs. revenue over time for both stocks

## Key Findings

- **Tesla (TSLA)**: Analyzed share price and revenue growth from 2010--2021. Identified significant price appreciation correlated with revenue expansion.
- **GameStop (GME)**: Analyzed share price and revenue trends from 2002--2021. Observed ~20% fluctuation patterns during peak trading periods, consistent with high volatility in the retail trading surge.

## Tech Stack

- **Python** (pandas, yfinance, requests, BeautifulSoup, Plotly)
- **Jupyter Notebook**

## Setup & Usage

```bash
pip install -r requirements.txt
jupyter notebook "Extracting and Visualizing Stock Data.ipynb"
```

Run all cells sequentially. The notebook will fetch live stock data and revenue tables, then generate interactive visualizations.

## License

MIT
