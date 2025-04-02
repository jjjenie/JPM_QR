# ![image](https://github.com/user-attachments/assets/8cbe9eb8-9c39-4b34-a9d5-01160b129823)
# 🔍 Retail Banking & Commodities Risk Analysis

This repository contains a collection of data analysis and machine learning solutions for predictive modeling in the banking and commodities sectors. It was developed as part of a quantitative research simulation, tackling real-world problems involving natural gas pricing, loan default prediction, contract valuation, and FICO score modeling.

---


## 📌 Tasks Overview

### Task 1 & 2: Natural Gas Price Forecasting + Contract Pricing
- **Goal:** Estimate future gas prices and value storage contracts.
- **Methods:** Seasonal regression using monthly prices, extrapolation, and cost-based valuation.
- **Files:** `natural_gas_forecast.py`, `gas_contract_pricing_model.py`

---

### Task 3 & 4: Loan Default Prediction & Expected Loss
- **Goal:** Predict loan default (PD) and estimate financial loss.
- **Methods:** Random Forest model using borrower features. Expected loss = PD × EAD × (1 - Recovery Rate).
- **Files:** `loan_expected_loss_model.py`

---

### Task 5: FICO Score Quantization
- **Goal:** Convert continuous FICO scores into buckets for categorical models.
- **Methods:** KMeans clustering to minimize variance within groups.
- **Files:** `fico_bucket_kmeans.py`




