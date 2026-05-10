# B9W1: Predicting Price Moves with News Sentiment

## Project Overview
This project analyzes the relationship between financial news sentiment and stock price movement for Nova Financial Solutions. The goal is to build an analytical pipeline that connects market narratives from financial news headlines with quantitative stock behavior.

## Business Objective
Nova Financial Solutions aims to improve predictive analytics by combining:
1. **Sentiment Analysis** — quantifying the tone of financial news headlines using NLP.
2. **Correlation Analysis** — measuring the relationship between news sentiment and daily stock returns.

## Interim Submission Progress

### Completed Task 1: News Exploratory Data Analysis
The Task 1 notebook includes:
- Headline length analysis
- Publisher activity analysis
- Publisher domain extraction
- Stock coverage analysis
- Daily publication volume trends
- Publication spike detection
- Publishing hour and day-of-week analysis
- CountVectorizer keyword analysis
- TF-IDF topic/term analysis
- Multiple labeled visualizations with interpretations

### Initial Task 2 Progress: Technical Indicators
The Task 2 notebook includes:
- Historical stock data loading
- Data quality checks
- Closing price trend visualization
- SMA calculation
- EMA calculation
- RSI calculation
- Daily return calculation
- Rolling volatility analysis

## Repository Structure

```text
news-sentiment-analysis/
├── .github/workflows/
│   └── unittests.yml
├── data/
│   └── raw/
├── notebooks/
│   ├── 01_news_eda.ipynb
│   └── 02_stock_indicator_analysis.ipynb
├── src/
│   └── __init__.py
├── tests/
│   ├── __init__.py
│   └── test_imports.py
├── scripts/
│   └── __init__.py
├── requirements.txt
├── .gitignore
└── README.md
```
## Setup Instructions
`git clone <repository-url>`
`cd news-sentiment-analysis`
`python3 -m venv .venv`
`source .venv/bin/activate`
`pip install -r requirements.txt`

## Run Tests
`pytest`

## Notebooks

| Notebook | Purpose |
|---|---|
| `01_news_eda.ipynb` | Exploratory analysis of financial news headlines, publishers, publication timing, stock coverage, and recurring themes |
| `02_stock_indicator_analysis.ipynb` | Initial quantitative stock analysis using technical indicators and return calculations |

## Tools and Libraries

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook
- pytest
- GitHub Actions

## Current Status

This repository contains the interim submission work:

- Completed Task 1
- Initial Task 2 progress
- CI/CD workflow
- Clean repository structure
- Reproducible environment setup

## Next Steps

The final submission will complete:

- Additional technical indicators including MACD
- Sentiment scoring using VADER or TextBlob
- News-stock date alignment
- Weekend and holiday handling
- Daily sentiment aggregation by stock
- Pearson correlation analysis
- Investment strategy recommendations


