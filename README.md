# Predict-Future-Stock-Prices
 Task Objective

This project builds a **GUI-based stock price prediction tool** using **Tkinter**, **yfinance**, and **Linear Regression**. Users can select from 15 popular stocks and visualize how well a model can predict closing prices based on historical data.

---

Dataset Used

- **Source**: Yahoo Finance (via `yfinance` API)
- **Period**: 1 Year Historical Data
- **Features Used**:
  - Open
  - High
  - Low
  - Volume
- **Target**:
  - Close Price

---

Models Applied

- **Linear Regression**:
  - Trained on `Open`, `High`, `Low`, and `Volume`
  - Predicts the `Close` price
  - Visual output: Actual vs Predicted line chart

---
Key Results and Findings

- Linear regression works fairly well for some stocks but not for all (since it’s a simple model).
- GUI makes it extremely easy to test different stocks without writing code.
- Application is extensible and can integrate more complex models in the future.

---
