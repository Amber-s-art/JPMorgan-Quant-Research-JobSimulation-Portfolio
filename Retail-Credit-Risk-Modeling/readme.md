# 🏦 Retail Credit Risk & Expected Loss Modeling

## Objective
To assist the retail banking risk team in estimating the Probability of Default (PD) on personal loans, enabling the bank to accurately set aside sufficient capital loss reserves for the upcoming year.

## The Quantitative Approach
This project focuses on translating raw borrower data into actionable risk metrics using industry-standard machine learning and feature engineering:

1. **Feature Engineering:** Calculated critical financial ratios relied upon in traditional credit underwriting, specifically **Debt-to-Income (DTI)** and **Payment-to-Income (PTI)**, to provide the model with highly predictive, normalized inputs.
2. **Predictive Modeling:** Deployed a highly interpretable Logistic Regression model to calculate the exact Probability of Default (PD) for individual borrowers based on their engineered financial profile.
3. **Financial Impact Valuation:** Designed a programmatic `calculate_expected_loss` function utilizing the standard regulatory formula: `EL = PD × Exposure at Default (EAD) × Loss Given Default (LGD)`.

## Results
The resulting tool acts as an automated underwriting assistant. It can ingest a hypothetical borrower's raw properties, automatically generate the required financial ratios, scale the inputs, and output the exact percentage likelihood of default alongside the projected monetary loss to the bank.
