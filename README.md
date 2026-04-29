# 🏦 JPMorgan Chase & Co. Quantitative Research Simulation

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-Time_Series-orange.svg)](https://www.statsmodels.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E?logo=scikit-learn)](https://scikit-learn.org/)

## 📌 Overview
This repository contains a suite of applied quantitative finance models developed during the **JPMorgan Chase & Co. Quantitative Research Job Simulation**. 

The simulation required acting as a quantitative researcher across multiple trading and risk desks. The projects demonstrate the ability to apply rigorous mathematical, statistical, and computer science techniques to solve real-world financial problems, from commodity trading to retail credit risk.

## 🗂️ Project Portfolio

### [1. Commodities Forecasting and Pricing Engine](./Commodities-Forecasting-and-Pricing)
**Domain:** Global Commodities Group
An end-to-end quantitative trading tool for natural gas. It features a continuous-time Harmonic Regression model to forecast seasonal prices and a dynamic pricing algorithm that calculates the Net Present Value (NPV) of physical storage contracts while programmatically enforcing strict facility capacity constraints.

### [2. Retail Credit Risk Modeling](./Retail-Credit-Risk-Modeling)
**Domain:** Retail Banking Risk
A machine learning pipeline built to estimate the Probability of Default (PD) on retail loans. It features financial ratio engineering (DTI and PTI) and deploys a Logistic Regression model to accurately calculate the Expected Loss for capital reserve provisioning.

### [3. FICO Score Quantization](./FICO-Score-Quantization)
**Domain:** Mortgage Risk Analytics
An advanced Dynamic Programming algorithm designed to "quantize" continuous FICO scores into optimal, discrete risk buckets. The model searches thousands of boundary combinations to find the exact breakpoints that mathematically maximize the Log-Likelihood of default density.

## 🛠️ Core Skills Demonstrated
* **Mathematical Modeling:** Harmonic Regression, Dynamic Programming, Log-Likelihood Optimization.
* **Financial Engineering:** Cash flow modeling, contract valuation, constraint processing, Expected Loss (EL) calculations.
* **Data Science:** Feature engineering (DTI/PTI ratios), predictive modeling (Logistic Regression), continuous-time series extrapolation.
* **Programming:** Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib).
