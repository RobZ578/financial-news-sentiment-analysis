# Predicting Price Moves with News Sentiment

## Project Overview
This repository contains the Week-1 project for Nova Financial Insights, focused on analyzing financial news headlines, computing sentiment, aligning data with stock price movements, and evaluating correlations between news sentiment and stock returns.

The goal is to understand how news sentiment affects stock price movements. The project involves:

- Exploratory Data Analysis (EDA) on financial news headlines
- Sentiment analysis using NLP tools (TextBlob/NLTK)
- Computing technical indicators using TA-Lib (SMA, EMA, RSI, MACD)
- Aligning news and stock price data by date
- Calculating daily stock returns
- Correlation analysis between sentiment and price movements
- Providing actionable insights based on the analysis

---

## Repository Structure

├── .vscode/
│ └── settings.json
├── .github/
│ └── workflows/
│ └── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│ ├── init.py
│ └── data_processing.py
├── notebooks/
│ ├── init.py
│ └── eda.ipynb
├── tests/
│ ├── init.py
│ └── test_utils.py
└── scripts/
├── init.py
└── run_analysis.py

markdown
Copy code

---

## Tasks Completed

### Task 1 — Git, GitHub, EDA, Environment Setup
- Created GitHub repository with proper folder structure
- Created branches: `task-1`, `task-2`, `task-3`
- Performed EDA:
  - Headline length statistics
  - Article distribution by publisher
  - Publication frequency trends over time
  - Keyword extraction and topic patterns
- Configured CI/CD workflow with GitHub Actions
- Set up Python environment with dependencies

### Task 2 — Quantitative Analysis (TA-Lib & PyNance)
- Loaded and cleaned historical stock price data
- Calculated technical indicators:
  - SMA / EMA
  - RSI
  - MACD
- Created visualizations for indicators vs. stock price
- Continued development in `task-2` branch

### Task 3 — Sentiment & Correlation Analysis
- Performed sentiment analysis on headlines (TextBlob/NLTK)
- Normalized timestamps and aligned stock + news datasets
- Calculated daily returns and aggregated daily sentiment
- Computed Pearson correlation coefficient between sentiment and stock returns
- Merged completed work into `main` via Pull Request

---

## Methods Used

- **Sentiment Analysis:** TextBlob polarity scoring, aggregated daily sentiment
- **Technical Indicators:** SMA, EMA, RSI, MACD
- **Stock Movement:** Daily returns (percentage change in Close price)
- **Correlation:** Pearson correlation coefficient, scatter plots for trend inspection

---

## How to Run

Clone repository:
git clone https://github.com/RobZ578/financial-news-sentiment-analysis.git
cd financial-news-sentiment-analysis

sql
Copy code

Create and activate environment:
python -m venv venv
source venv/bin/activate # macOS/Linux
venv\Scripts\activate # Windows

yaml
Copy code

Install dependencies:
pip install -r requirements.txt

yaml
Copy code

Run analysis:
python scripts/run_analysis.py

yaml
Copy code

---

## Tools and Technologies

- Python 3
- Pandas, NumPy
- TA-Lib
- PyNance
- NLTK / TextBlob
- Matplotlib / Seaborn
- Git & GitHub
- GitHub Actions (CI/CD)

---

## References

- https://www.investopedia.com/terms/s/stockmarket.asp
- https://textblob.readthedocs.io/en/dev/
- https://mrjbq7.github.io/ta-lib/
- https://github.com/mqandil/pynance
- https://www.atlassian.com/git
