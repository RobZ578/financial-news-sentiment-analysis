Predicting Price Moves with News Sentiment

Financial News + Stock Price Integration | NLP + Quantitative Analysis

This repository contains my Week-1 project for Nova Financial Insights.
The goal is to analyze financial news headlines, compute sentiment, align the data with stock movements, and evaluate correlations between sentiment and stock price returns.

Project Overview

The project focuses on:

Exploratory Data Analysis (EDA) on financial news

Sentiment analysis on headlines

Quantitative analysis using TA-Lib and PyNance

Technical indicators (RSI, SMA, EMA, MACD)

Computing daily stock returns

Correlation analysis between sentiment and price movement

Building a reproducible data-science environment with GitHub version control

Repository Structure
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
│   └── data_processing.py
├── notebooks/
│   ├── __init__.py
│   └── eda.ipynb
├── tests/
│   ├── __init__.py
│   └── test_utils.py
└── scripts/
    ├── __init__.py
    └── run_analysis.py

Tasks Completed
Task 1 — Git, GitHub, EDA, Environment Setup

Created GitHub repo with recommended folder structure

Created branches: task-1, task-2, task-3

Performed EDA:

Headline length statistics

Article distribution by publisher

Publication frequency over time

Keyword extraction and topic patterns

Set up CI/CD workflow using GitHub Actions

Created and configured Python environment

Task 2 — Quantitative Analysis (TA-Lib & PyNance)

Loaded and cleaned stock price data

Calculated technical indicators:

SMA/EMA

RSI

MACD

Visualized technical indicators

Continued development in task-2 and merged using Pull Request

Task 3 — Sentiment & Correlation Analysis

Performed sentiment analysis using TextBlob/NLTK

Cleaned and normalized timestamps

Merged news dataset with stock dataset based on dates

Calculated daily returns

Aggregated daily sentiment

Performed Pearson correlation analysis

Merged completed work into main using Pull Request

Methods Used
Sentiment Analysis

TextBlob polarity scoring

Aggregated average daily sentiment

Technical Indicators (TA-Lib)

Simple Moving Average (SMA)

Exponential Moving Average (EMA)

Relative Strength Index (RSI)

Moving Average Convergence Divergence (MACD)

Stock Movement

Daily returns (percentage change)

Correlation

Pearson correlation coefficient

Scatter plots and trend inspection

Reports
Interim Report

Covers Task 1 and partial Task 2

Maximum length: 3 pages

Final Report

Covers all tasks

Up to 10 pages including plots

Medium-style publication formatting

How to Run the Project

Clone repository:

git clone https://github.com/USERNAME/financial-news-sentiment-analysis.git
cd financial-news-sentiment-analysis


Create and activate environment:

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt


Run analysis:

python scripts/run_analysis.py

Tools and Technologies

Python 3

Pandas, NumPy

TA-Lib

PyNance

NLTK / TextBlob

Matplotlib / Seaborn

Git & GitHub

GitHub Actions (CI/CD)

References

Investopedia — Stock Market and Analysis

TextBlob Documentation

TA-Lib Python Docs

PyNance GitHub

Atlassian Git, CI/CD Guides  
