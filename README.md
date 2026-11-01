# Financial-Econometrics-Data-Analysis
A financial econometrics project that applies Python to analyze U.S. equity market data through data preprocessing, exploratory analysis, feature engineering, visualization, and statistical techniques for quantitative finance research.
# 📈 Financial Econometrics Data Analysis

## Machine Learning for Financial Markets

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## Project Overview

This project explores financial econometrics and machine learning using historical U.S. stock market data.

Instead of relying solely on statistical summaries, the project combines:

- Financial time-series analysis
- Feature engineering
- Machine learning classification
- Trading simulations
- Model evaluation

The objective is to understand whether historical market information can be transformed into profitable investment signals.

---

# Project Workflow

---

# Stock Price Behaviour

Understanding how prices evolve over time is the first step toward building predictive models.

![Stock Price](images/stock-price.png)

The figure above shows the historical daily price movement of Novo Nordisk (NVO). Strong upward momentum is observed until mid-2024, followed by a significant correction and stabilization period. Such structural changes motivate the need for predictive modelling rather than simple trend following.

---

# Growth Distribution

Financial returns rarely follow perfectly normal distributions.

![Growth Distribution](images/growth-distribution.png)

Daily growth rates are tightly concentrated around zero, while longer investment horizons exhibit greater variability. This observation motivates forecasting future returns rather than relying on daily price movements alone.

---

# Two-Day Growth Distribution

![Growth Histogram](images/two-day-growth.png)

The histogram illustrates the distribution of two-day growth rates. Most observations cluster near the mean, while extreme positive and negative returns occur less frequently. Understanding this distribution helps define meaningful prediction targets.

---

# Target Variable Analysis

Before training machine learning models, the target variable is examined to understand class balance.

![Target Distribution](images/target-distribution.png)

Approximately half of the observations correspond to positive future returns, creating a balanced classification problem suitable for supervised learning.

---

# Interest Rate Curve

Macroeconomic indicators are valuable predictors in financial modelling.

![Yield Curve](images/yield-curve.png)

The AAA-rated bond yield curve provides information about market expectations and economic conditions. Yield curves are frequently incorporated into quantitative finance models to improve predictive performance.

---

# Machine Learning Performance

Model quality is evaluated using Precision, Recall, and F1-score across multiple probability thresholds.

![Precision Recall](images/precision-recall.png)

The Decision Tree model achieves its highest F1-score near the optimal probability threshold, demonstrating the importance of threshold selection when balancing false positives and false negatives in financial decision-making.

---

# Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- yFinance
- Google Colab
- Jupyter Notebook

---

# Repository Structure

