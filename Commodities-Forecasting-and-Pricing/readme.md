# 🛢️ Commodities Forecasting & Contract Pricing Engine

## Objective
To build an automated quantitative tool that forecasts seasonal commodity prices and calculates the fair value of physical natural gas storage contracts based on operational cash flows and facility limitations.

## The Quantitative Approach
This project merges time-series statistics with financial cash-flow modeling:

**1. Continuous-Time Harmonic Regression (Forecasting)**
* Modeled time as a continuous linear trend (`Days since start`) rather than discrete monthly steps.
* Engineered sine and cosine waves (Fourier terms) for both Annual and Semi-Annual cycles to capture complex, dual-peak seasonal market behaviors mathematically.
* Fitted the features using Ordinary Least Squares (OLS) to create an interpolation/extrapolation function capable of estimating the price on any specific historical or future date.

**2. Algorithmic Contract Valuation (Pricing Engine)**
* Built a dynamic engine that integrates the forecasting model to automatically price future trades.
* Implemented chronological event sorting to simulate complex, interleaved trading schedules day-by-day.
* Programmatically enforced real-world physics and facility rules, throwing errors if a trade attempts to exceed cavern capacity, breach injection/withdrawal pipe limits, or sell non-existent inventory.

## Results
The combined engine allows a desk trader to input a proposed schedule of injections and withdrawals. It instantly forecasts the required seasonal prices, tracks the running physical inventory, deducts all transport and rental fees, and outputs a clean, auditable receipt of the Net Contract Value.
