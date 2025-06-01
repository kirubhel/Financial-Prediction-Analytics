
# 📈 Financial Prediction with News Sentiment – B5W1 Challenge

This project explores the relationship between financial news sentiment and stock market movement. It is developed as part of the **10 Academy B5W1 Challenge** using a blend of natural language processing, financial analytics, and statistical modeling.

---

## 📁 Project Structure

```
Financial-Prediction-Analytics/
├── .github/workflows/         # GitHub Actions CI/CD
├── data/                      # News and stock price datasets
├── notebooks/                 # Jupyter Notebooks for analysis
├── scripts/                   # Any reusable scripts (optional)
├── src/                       # Python modules
├── tests/                     # Unit tests
├── requirements.txt           # Python dependencies
├── README.md                  # This file
└── .gitignore                 # Files to exclude from Git
```

---

## ✅ Tasks Overview

### 📊 Task 1: Exploratory Data Analysis (EDA)
- Analyzed headline lengths and frequency by publisher
- Identified publishing trends over time
- Generated word clouds and extracted high-frequency terms

### 📉 Task 2: Quantitative Analysis with TA-Lib and PyNance
- Downloaded stock price data with `yfinance`
- Applied indicators: MA, RSI, MACD using `TA-Lib`
- Visualized trends in price movement and indicators

### 🧠 Task 3: Sentiment vs. Return Correlation
- Performed sentiment analysis on news headlines using `TextBlob`
- Computed daily stock returns from historical stock data
- Merged sentiment with returns by date and calculated correlation
- Visualized sentiment vs return relationship using scatter plots

---

## ⚙️ Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **NLP**: TextBlob, NLTK
- **Finance Tools**: TA-Lib, yFinance, PyNance
- **CI/CD**: GitHub Actions
- **Version Control**: Git, GitHub

---

## 🧪 Testing

Run all tests with:
```bash
python -m unittest discover tests
```

---

## 📦 Setup

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ✍️ Author

- **Kirubel Gizaw**
- B5W1 Trainee – 10 Academy

---

## 📄 Final Report

The final report includes insights, code methodology, and plots. It is available in the repository or submitted separately via the 10 Academy platform.

---

## 🔗 Challenge Reference

- [B5W1 Overview](https://kaimtenx.10academy.org/trainee/challenge/B5W1)
- Reference GitHub Repo: [https://github.com/kirubhel/Financial-Prediction-Analytics]

---
