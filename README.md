# 📈 Industry Unit Demand Prediction – Time Series Forecasting for Electric Forklifts  
**MS Practicum Capstone – University at Buffalo**  
**In Collaboration with Raymond Corporation (Toyota Industries)**  
**Date:** May 2, 2025

## 📌 Project Overview
This capstone project was conducted in partnership with Raymond Corporation to enhance the accuracy of demand forecasting for electric forklifts in a post-COVID economy. The legacy forecasting models were insufficient in handling volatile demand patterns. Our goal was to build a robust, data-driven model capable of accurately forecasting unit sales for 2025–2026 using time series and regression techniques.

---

## 🎯 Problem Statement
- **Pre-COVID Era (2019–2020):** Demand was relatively stable and predictable.
- **COVID Impact (2021):** Demand surged ~60% due to exponential growth in e-commerce.
- **Post-COVID Volatility:** Demand declined by ~25% over the next two years.
- **Challenge:** Legacy predictive models failed to adapt to these rapid demand shifts.
- **Objective:** Deliver improved demand forecasts to inform strategic production planning.

---

## 🔍 Approach

### 1. **Exploratory Data Analysis (EDA)**
- Assessed trends, seasonality, and anomalies.
- Investigated economic indicators and their correlation with forklift sales.

### 2. **Feature Engineering**
- Incorporated external macroeconomic indicators:
  - **Interest Rates (10- & 20-year treasury yields)**
  - **Consumer Confidence Index (CCI)**
  - **Consumer Price Index (CPI) growth**
  - **Retail Trade Volumes**

### 3. **Model Building**
- Evaluated multiple models:
  - **ARIMA/SARIMA** for time series forecasting.
  - **Multiple Linear Regression** for demand estimation using predicted economic indicators.
- Model selection based on **Adjusted R²** and **RMSE**.

### 4. **Forecasting Input Variables**
- Forecasted external economic indicators using SARIMA.
- These predictions served as inputs for final regression-based demand forecasting.

---

## 🔧 Tools & Technologies
- Python (Time Series Modeling, Regression Analysis)
- R (initial modeling scripts, later converted to Python via client’s Enterprise GPT)
- Jupyter Notebooks
- External APIs and public datasets for economic indicators

---

## 📊 Model Output
- Forecasted demand for electric forklifts (by class/lift code) for **2025–2026**
- Insights delivered via a clean, interpretable output format for business use
- Designed for easy updating as new economic data becomes available

---

## 🔐 Data Privacy and Security
- **Confidential Client Data:** Not included in this repository
- **Security Measures:**
  - All development done using client’s enterprise systems
  - Code shared only in protected environments
  - No sensitive data shared externally

---

## 🧠 Key Learnings
- Data-driven models outperform heuristic forecasting under volatile conditions
- Forecast accuracy improves significantly when combining time series and regression
- Economic indicators can serve as leading indicators for product demand

---

## 🔄 Next Steps & Enhancements
- Add **Monte Carlo Simulation** to quantify uncertainty and scenario analysis
- Parameterize external shocks such as **tariffs** or **recessions**
- Evaluate alternative forecasting models like **Prophet** or **LSTM networks**

---

## 📚 References & Data Sources
- [U.S. Treasury Reporting Rates](https://fiscaldata.treasury.gov/datasets/treasury-reporting-rates-exchange/treasury-reporting-rates-of-exchange)  
- [Macrotrends – U.S. GDP Growth](https://www.macrotrends.net/global-metrics/countries/USA/united-states/economic-growth-rate)  
- [U.S. Bureau of Labor Statistics – Inflation](https://www.usinflationcalculator.com/inflation/current-inflation-rates/)

---

## ⚠️ Disclaimer
This repository does **not** contain proprietary data, code, or business-sensitive information from Raymond Corporation. All modeling was performed with strict adherence to client confidentiality agreements.

