# Fuel Price Impact on Transport Inflation in India

## Project Overview
This project investigates the relationship between **fuel price indices** and **transport-related inflation (CPI)** in India using **Machine Learning** and **Econometric techniques**. It seeks to quantify the domestic and global price impact on CPI components, using actual data and predictive models, presented as a fully deployable and explainable ML-based econometric workflow.

---

## Objective
To build and evaluate **regression-based ML models** that quantify how **Crude Oil Price (USD)** and **Retail Fuel Price (INR)** influence **Transport CPI in India**, thus offering real-world insights into the structure and triggers of transport inflation.

---

## Domain Context
- **Domain**: Economics + Data Science
- **Sub-domain**: Price Indices, CPI Components, Energy Economics
- **Primary Econometric Concern**: Fuel Price Transmission Effect
- **Real-time Insight**: How macro (global) and micro (domestic) fuel price factors influence inflation patterns within transport categories in India.

---

## Tools & Techniques Used

### Econometric Foundations:
- **Price Elasticity & Pass-Through Effects**
- **Univariate and Multivariate Linear Regression**
- **Outlier Consideration (e.g., Kerosene)**
- **Interpretability Focus with Coefficients and Error Metrics**

### Machine Learning Models:
- `LinearRegression()` — for both univariate and multivariate modeling
- `Ridge()` — applied in Phase 1 of the earlier experimentation for robustness (optional)

### Performance Metrics:
- R² Score (Goodness of Fit)
- MAE (Mean Absolute Error)
- RMSE (Root Mean Square Error)

---

## Project Structure

fuel_transport_regression_project_v2/
├── data/
│ ├── raw/ # Raw CSVs (crude oil, transport CPI, fuel prices)
│ └── processed/ # Cleaned and merged dataset
├── notebooks/
│ └── Fuel_transport_regression_project_v2.ipynb
├── output/
│ ├── plots/ # Regression visualizations
│ └── results/ # Model predictions and CSV outputs
└── README.md # You're reading it.


---

## Project Phases

### Phase 1: Crude Oil Price (USD) vs Transport CPI — [Univariate Regression]
- Built foundational model using global oil prices
- R² Score was low (~0.15), establishing weak standalone explanatory power
- Insight: Global crude alone cannot capture domestic inflation drivers

### Phase 2: Crude + Retail Fuel Price vs Transport CPI — [Bivariate Regression]
- Introduced Retail Fuel Price (INR) as a second independent variable
- Result: **R² = 0.9189**, major improvement in accuracy
- Significantly reduced MAE and RMSE — stronger real-world alignment

---

## Key Takeaways

- **Crude Oil (USD)** shows influence, but limited as a sole factor
- **Retail Fuel Price (INR)** strongly correlates with Transport CPI
- Combined model performs better and is **economically realistic**
- Suggests the need for **macro + micro signal integration** in ML pipelines

---

## Dataset Sources
- [Ministry of Petroleum & Natural Gas](https://ppac.gov.in)
- [MOSPI CPI Index Archives](https://mospi.gov.in)
- [Trading Economics: Crude Oil Data](https://tradingeconomics.com)
- [Retail Fuel Prices in India (Historical Archives)](https://data.gov.in)

---

## Learnings & Reflection

This project emphasized:
- The **importance of economic logic** before blindly applying ML
- How **ML + Econometrics** can coexist for real-world interpretability
- GitHub workflow and reproducibility in data science deployment
- A replicable structure for **cross-country or sector-specific economic modeling**

---

## Author

**Sai Sarat Chandra**  
*Data Science & AI | Economics & Research Enthusiast*  

---

> “This is not just a regression model — it's a real-world econometric lens.”  
> Let this project inspire the rest of the pipeline.