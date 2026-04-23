# 🦠 COVID-19 Data Analysis using Machine Learning

A Python-based data analysis and machine learning project built in Jupyter Notebook to explore COVID-19 trends and forecast future case counts using multiple ML models.

---

## 📋 About the Project

This project analyzes COVID-19 case data from January 2020 to May 2021, with a deep focus on India — covering lockdown-phase analysis, recovery and mortality trends, and comparisons with other countries. It applies four machine learning models to predict confirmed cases 100 days into the future.

---

## 👥 Authors

**Mrunal Howale** · **Shreyash Ingale** · **Nainesh Bait** · **Aditi Jadyal**
BE EXTC-1 — Atharva College of Engineering, Mumbai
*Guide: Prof. Shikha Malik*

---

## 🛠️ Tech Stack

- 🐍 **Python** — Core programming language
- 📓 **Jupyter Notebook** — Development environment
- 📊 **Pandas & NumPy** — Data manipulation and analysis
- 📈 **Plotly, Matplotlib & Seaborn** — Visualizations
- 🤖 **Scikit-learn** — Polynomial Regression and SVR
- 📉 **Statsmodels** — ARIMA time series model
- 🔮 **FB Prophet** — Facebook's time series forecasting library

---

## 📂 Data Source

**Source:** [Kaggle — Novel Corona Virus 2019 Dataset](https://www.kaggle.com/datasets/sudalairajkumar/novel-corona-virus-2019-dataset) (originally from Johns Hopkins University)

Covers daily Confirmed, Recovered, and Death case counts across countries from **January 2020 to May 2021**.

---

## 📒 Notebook Overview

The notebook is structured into the following sections:

**1. Exploratory Data Analysis (India)**
- Confirmed, recovered, active, and death case trends over time
- Daily and weekly breakdowns
- Recovery rate, mortality rate, and growth factor analysis
- Doubling and tripling rate of confirmed cases

**2. Lockdown Phase Analysis**
- Case growth broken down across No Lockdown, Lockdown 1.0–4.0, and Unlock 1.0 phases

**3. Country Comparisons**
- India vs. neighbouring countries: Pakistan, China, Afghanistan, Nepal, Bhutan, Sri Lanka, Bangladesh
- India vs. worst-hit countries: USA, Italy, Spain, France, UK, Brazil, Iran

**4. Machine Learning Predictions (100-day forecast)**

| Model | Type |
|---|---|
| Polynomial Regression (degree 6) | Supervised Regression |
| Support Vector Regression (SVR) | Supervised Regression |
| ARIMA | Time Series Forecasting |
| FB Prophet | Time Series Forecasting |

Models were evaluated using RMSE and RMSPE to identify the best-performing approach.
