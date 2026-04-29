# 🏦 JPMorgan Chase & Co. Quantitative Research Simulation

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-Time_Series-orange.svg)](https://www.statsmodels.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E?logo=scikit-learn)](https://scikit-learn.org/)

## 📌 Overview
This repository contains a suite of applied quantitative finance models developed during the **JPMorgan Chase & Co. Quantitative Research Job Simulation**. 

The simulation required acting as a quantitative researcher across multiple trading and risk desks. The projects demonstrate the ability to apply rigorous mathematical, statistical, and computer science techniques to solve real-world financial problems, from commodity trading to retail credit risk.

## 🗂️ Project Portfolio

### [1. Continuous-Time Commodity Forecasting](./Commodity-Price-Forecasting)
**Domain:** Global Commodities Group
Developed a continuous-time forecasting model using Harmonic Regression to estimate natural gas prices for any given historical or future date. The model successfully captures complex, overlapping annual and semi-annual seasonal demand cycles using Fourier terms.

### [2. Algorithmic Storage Contract Pricing](./Algorithmic-Contract-Pricing)
**Domain:** Commodities Trading Desk
Engineered a dynamic pricing prototype that calculates the Net Present Value (NPV) of physical natural gas storage contracts. The algorithm accounts for multiple cash flows (injection, withdrawal, transport, and storage rent) while programmatically enforcing strict physical capacity and flow-rate constraints.

### [3. Retail Credit Risk & FICO Quantization](./Credit-Risk-Quantization)
**Domain:** Retail Banking Risk
Built a machine learning pipeline to estimate the Probability of Default (PD) on retail loans. Engineered a mathematically rigorous Dynamic Programming (DP) algorithm to "quantize" continuous FICO scores into optimal risk buckets by maximizing the Log-Likelihood of default density.

## 🛠️ Core Skills Demonstrated
* **Mathematical Modeling:** Harmonic Regression, Dynamic Programming, Log-Likelihood Optimization.
* **Financial Engineering:** Cash flow modeling, contract valuation, constraint processing.
* **Data Science:** Feature engineering (DTI/PTI ratios), predictive modeling (Logistic Regression), time-series interpolation/extrapolation.
* **Programming:** Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib).
