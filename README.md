# Natural Gas Price Forecasting & Extrapolation

## Overview

This project focuses on **forecasting and extrapolating natural gas prices** using historical time-series data. The objective is to identify trends, seasonality, and price patterns to support **pricing, storage planning, and strategic decision-making**.

The project demonstrates hands-on skills in **Python-based time-series analysis, regression modeling, and data visualization**, packaged as an end-to-end data analytics and forecasting case study.

---

## Dataset

* **Data Type:** Historical natural gas prices
* **Time Period:** 2020 – 2024
* **Granularity:** Time-series (date-wise pricing)
* **Key Fields:** Date, Price

The dataset captures seasonal and long-term price movements relevant to energy markets and storage contracts.

---

## Tools & Technologies

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn
* **Modeling:** Linear Regression
* **Environment:** Jupyter Notebook
* **Version Control:** Git & GitHub

---

## Project Steps

1. **Data Loading**

   * Imported historical price data using Pandas

2. **Exploratory Data Analysis (EDA)**

   * Analyzed price trends over time
   * Identified seasonality and volatility patterns

3. **Feature Engineering**

   * Extracted time-based features (year, month)
   * Prepared data for regression modeling

4. **Model Development**

   * Built a **Linear Regression model** to forecast prices
   * Trained the model on historical data

5. **Forecasting & Extrapolation**

   * Generated past and future price predictions
   * Implemented a **date-input function** for dynamic forecasts

6. **Visualization**

   * Plotted historical vs. predicted prices
   * Visualized seasonal and monthly trends using Matplotlib

---

## Results & Insights

* The model successfully captures **overall price trends and seasonality**
* Forecasts provide a clear view of potential future price movements
* Useful for **storage contract pricing, budgeting, and risk assessment**

---

## Use Cases

* Energy price trend analysis
* Storage and contract pricing support
* Scenario analysis for procurement and trading decisions

---

## How to Run the Project

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   ```

2. **Install Dependencies**

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. **Run the Notebook**

   * Open `Natgas Price Prediction.ipynb` in Jupyter Notebook
   * Run all cells to reproduce the analysis and forecasts

4. **Modify Inputs**

   * Use the date-input function to generate custom price predictions

---

## Limitations & Future Improvements

* Linear regression may not fully capture market shocks or extreme volatility
* Future enhancements could include:

  * ARIMA / SARIMA models
  * Machine learning or deep learning models (XGBoost, LSTM)
  * External factors such as demand, weather, and macroeconomic indicators

---

## Author

**Kaustubh Upade**
Data Analyst | Python | Time-Series Analysis | Forecasting

This project is part of my data analytics portfolio and highlights practical forecasting and analytical skills applied to real-world energy market data.
