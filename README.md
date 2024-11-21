# Cryptocurrency Analysis and Google Sheets Integration

## Overview
This project fetches live cryptocurrency data for the top 50 cryptocurrencies by market capitalization using the CoinGecko API. The data is analyzed to extract key insights and is automatically updated into a Google Spreadsheet in real time. The project is designed to help analysts, investors, and enthusiasts understand market trends, volatility, and key performance metrics.

---

## Features
- Fetches live data for the top 50 cryptocurrencies.
- Analyzes key metrics such as:-
  - Top 5 cryptocurrencies by market capitalization.
  - Average price of the top 50 cryptocurrencies.
  - Highest and lowest 24-hour percentage price changes.
- Automatically updates data into a Google Spreadsheet every 5 minutes.
- Provides a comprehensive analysis report with insights into market concentration, volatility, and price distribution.

---

## Technologies Used
- **Python**: For data fetching, analysis, and integration.
- **CoinGecko API**: To retrieve live cryptocurrency data.
- **gspread**: For interacting with Google Sheets.
- **Google Sheets API**: For real-time data updates.
- **OAuth 2.0**: For secure authentication with Google Sheets.

---

## Setup Instructions

### 1. Prerequisites
- Python 3.8 or higher
- Google Cloud account with API access
- CoinGecko API (no authentication required)

### 2. Install Required Libraries
Run the following command to install dependencies:
```bash
pip install requests gspread oauth2client
```

## Future Enhancements
- Add graphical visualizations to the Google Spreadsheet.
- Implement error handling for API rate limits or connection failures.
- Support additional metrics like trading pairs or historical trends.
- Expand the analysis to include sentiment analysis using social media data.

## Contacts 

- Linkedin -[Sneha Vilasrao Pujari](https://www.linkedin.com/in/sneha-vilasrao-pujari/)
- Gmail - dotsnehapujari555@gmail.com

