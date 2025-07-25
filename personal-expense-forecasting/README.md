# Personal Expense Forecasting (2013–2025)

This project analyzes **12 years of personal expense data** and uses **time series forecasting** to estimate future spending.  
The goal is to understand long-term spending habits, predict upcoming expenses, and use these insights for financial planning.

This README file is mostly AI generated.

---

## 🔍 **Overview**

- **Dataset:** 5,400+ expense records from 2013–2025  
- **Objective:** Forecast monthly spending using both **statistical** and **machine learning** models  
- **Key Questions:**  
  - How have my expenses evolved over time?  
  - What is my expected monthly spending over the next 6 months?  
  - How do statistical and ML models compare in forecasting accuracy?  

---

## 🛠 **Techniques Used**

- **Time Series Analysis:**  
  - ARIMA (AutoRegressive Integrated Moving Average)  
  - Stationarity testing (ADF)  
  - Residual diagnostics and model selection via AIC/BIC  

- **Machine Learning:**  
  - Gradient Boosting (LightGBM)  
  - Lag and rolling feature engineering  
  - Time-based train/test split and evaluation (RMSE, MAE)  

- **Visualization:**  
  - Matplotlib, Seaborn, and Plotly for interactive insights  

---

## 📂 **Project Structure**

1. **Data Cleaning & Preparation**  
   - Parsing dates, creating time-based features  
   - Aggregating monthly totals  

2. **Exploratory Time Series Analysis**  
   - Trend plots, rolling averages, seasonal patterns  
   - Outlier detection  

3. **ARIMA Forecasting**  
   - Model tuning and residual diagnostics  
   - Forecast future monthly expenses (6 months)  

4. **LightGBM Forecasting**  
   - Feature-driven predictions using lag and rolling stats  
   - Comparison with ARIMA predictions  

5. **Model Comparison & Insights**  
   - How forecasts differ between statistical and ML approaches  
   - Implications for financial planning  

---

## 📊 **Key Insights**

- **ARIMA (recent era)** predicts **higher monthly expenses**, reflecting my current cost of living.  
- **ARIMA (full history)** gives a **more conservative estimate**, averaging past lifestyle patterns.  
- **LightGBM** captured **short-term dynamics** but was less sensitive to long-term shifts.  
- Life events (e.g., upcoming **destination weddings**) may cause deviations — models help flag these as anomalies.

---

## 🌱 **Applications Beyond Personal Finance**

While this analysis focuses on expenses, the same techniques can be adapted to:
- **Athlete performance forecasting** (tracking progress, peak prediction)
- **Small business / non-profit financial planning** (cash flow, donations, operational costs)
- **Any domain where temporal patterns drive decision-making**

---

## ▶️ Usage Notes

- The dataset used in this project is **personal and not shared publicly**.  
- The notebook is included as a **read-only portfolio piece** to demonstrate:
  - Data cleaning and feature engineering workflow
  - Time series forecasting with ARIMA
  - Machine learning forecasting with LightGBM
  - Model comparison and interpretation
