# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index)** and **Hyperliquid historical trader performance**. The objective is to identify how different market sentiment regimes influence trader profitability, trading behavior, and decision-making.

The analysis includes data cleaning, exploratory data analysis (EDA), statistical testing, and visualization to uncover actionable insights that can support smarter trading strategies.

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index

* Date
* Classification
* Fear & Greed Value

### 2. Hyperliquid Historical Trader Data

* Account
* Coin
* Side
* Size USD
* Closed PnL
* Execution Price
* Timestamp
* Timestamp IST
* Direction

---

## Project Objectives

* Clean and preprocess both datasets.
* Merge trader activity with daily market sentiment.
* Analyze trader performance across different sentiment categories.
* Discover hidden behavioral patterns.
* Generate meaningful insights using visualizations and statistical analysis.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Jupyter Notebook

---

## Analysis Performed

* Data Cleaning and Preprocessing
* Data Merging
* Exploratory Data Analysis (EDA)
* Profit & Loss Analysis
* Win Rate Analysis
* Position Size Analysis
* Buy vs Sell Behavior
* Account-wise Performance Analysis
* Statistical Comparison Across Market Sentiments

---

## Key Findings

* Trader performance does not increase linearly with market sentiment. Instead, the strongest performance is observed during **Fear** and **Extreme Greed** market conditions.

* Traders tend to increase their average position sizes during **Fear**, indicating greater conviction during market pullbacks.

* Buying activity is more prominent during Fear, while selling activity increases during Extreme Greed, suggesting a largely contrarian trading approach.

* Market sentiment alone is a weak predictor of profitability. It is more effective when used as a market regime indicator alongside other trading signals.

---

## Project Files

This repository contains:

* `trader_sentiment_analysis.ipynb` – Complete analysis notebook
* `Trader_Sentiment_Insights_Report.docx` – Detailed project report
* Historical Trader Dataset
* Bitcoin Fear & Greed Dataset
* Generated visualizations (if included)

---

## Results

The project successfully combines market sentiment with historical trading data to evaluate how trader behavior changes under different market conditions. The findings provide insights into profitability trends, trading strategies, and sentiment-driven market behavior.
