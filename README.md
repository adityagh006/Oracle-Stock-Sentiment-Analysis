# 📈 Oracle Stock Sentiment Analysis (September 2025 Surge)

This project analyzes the relationship between Oracle's stock price movement and news sentiment around the major price surge on September 10, 2025. It uses stock data from Yahoo Finance and news sentiment scores computed using NLTK and VADER.

## 🔍 Project Overview

- Fetches Oracle (ORCL) stock data from Yahoo Finance
- Gathers related news articles using NewsAPI
- Cleans and preprocesses article headlines using:
  - Tokenization
  - Stopword removal
- Applies VADER Sentiment Analysis to generate sentiment scores
- Aggregates sentiment by date
- Visualizes:
  - Oracle closing stock price
  - Daily aggregated sentiment score
  - Highlights the Sept 10, 2025 stock surge and related sentiment

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Yahoo Finance (`yfinance`)
- NewsAPI
- NLTK
- VaderSentiment
- Matplotlib
- Pandas

## 📊 Key Features

- **Data Collection**: Automated fetching of historical stock prices and news articles
- **Text Preprocessing**: Robust cleaning pipeline for news headlines
- **Sentiment Scoring**: VADER-based sentiment analysis for financial news
- **Data Aggregation**: Daily sentiment score averaging for trend analysis
- **Visualization**: Clear charts showing stock price movement alongside sentiment trends

## 🚀 Getting Started

### Prerequisites
```bash
pip install yfinance newsapi-python nltk matplotlib pandas vaderSentiment
```

### Usage

1. Clone the repository
2. Add your NewsAPI key to the configuration
3. Run the Jupyter Notebook
4. Analyze the visualizations and insights

## 📈 Analysis Focus

The project specifically examines the **September 10, 2025** stock surge, correlating price movements with news sentiment to understand market reaction to Oracle-related news during this period.
