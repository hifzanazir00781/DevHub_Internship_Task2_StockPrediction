# 📈 Stock Price Prediction: Short-Term Forecasting (AAPL)

**Developer:** Hifza Nazir — AI Engineering Intern  
**Organization:** DevelopersHub Corporation  
**Task:** 02 - Stock Market Trend Prediction  
**Date:** 10 February 2026

---

## 📌 Project Overview
The objective of this project is to predict the short-term future closing prices of a stock (specifically Apple Inc. - AAPL) using historical market data. By analyzing daily features like Open, High, Low, and Volume, the model establishes a baseline for predicting price movements, demonstrating the application of regression analysis in financial markets.

---

## 🛠️ Technical Workflow & Implementation

### 1. Real-Time Data Acquisition
* **Library**: Utilized `yfinance` to fetch live historical market data.
* **Period**: Data analyzed from **January 2024 to February 2026**.
* **Features**: Market indicators including `Open`, `High`, `Low`, and `Volume`.

### 2. Feature Engineering & Preparation
* **Target Variable**: Created a `Target_Close` column by shifting the actual closing prices by -1, allowing the model to learn the correlation between current indicators and the next day's outcome.
* **Data Cleaning**: Handled missing values (NaN) resulting from the data shift to ensure a continuous training set.
* **Train-Test Split**: Implemented an 80/20 split for robust model validation.

### 3. Model Architecture
* **Algorithm**: **Linear Regression**.
* **Rationale**: Chosen for its efficiency in identifying linear trends within time-series financial data.
* **Evaluation Metric**: Visualized performance through **Actual vs. Predicted** price trend comparisons.

---

## 📊 Performance & Insights


### Key Observations:
* **Trend Following**: The model successfully captures the general upward or downward trajectory of the stock price.
* **Baseline Accuracy**: While financial markets are influenced by external volatility (news, events), the model provides a solid mathematical baseline for short-term price movements.
* **Volatility Gaps**: Minor deviations in the graph highlight the inherent risk and volatility in stock market forecasting.

---

## 🧬 Key Skills Demonstrated
* **Financial Data Analysis**: Fetching and processing real-world stock market data.
* **Time-Series Preparation**: Implementing "shifting" techniques for future value prediction.
* **Regression Modeling**: Applying Linear Regression to complex financial datasets.
* **Data Visualization**: Creating high-fidelity comparative plots using Matplotlib.

---
**Project Status:** ✅ Completed  
**Contact:** [Hifza Nazir](https://github.com/hifzanazir00781)  
*Final Submission for Task 2 | AI Engineering Internship*
