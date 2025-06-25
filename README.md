
# 🚗📊 Fuel Price Impact on Transport Inflation in India (Bivariate Regression)

This project analyzes how **Crude Oil Prices (USD)** and **Retail Fuel Prices (INR)** influence **Transport & Communication CPI** in India using a **Bivariate Linear Regression** model.

---

## 🔍 Objective

To evaluate the combined impact of global crude oil prices and domestic retail fuel prices on India's transport-related inflation using regression analysis.

---

## 📦 Dataset

- Monthly **CPI data** from MoSPI (India)
- **Crude Oil Prices (USD)** – global benchmark
- **Retail Fuel Prices (INR)** – simulated for analysis

---

## ⚙️ Methodology

- **Data Processing:** Cleaned, aligned, and merged all inputs
- **Phase 2:** Univariate Regression using crude oil price
- **Phase 3:** Bivariate Regression including retail fuel price
- **Evaluation:** Metrics like R², MAE, RMSE
- **Visualization:** 3D regression plot for better interpretation

---

## 📊 Output Summary

- 📄 `bivariate_metrics.csv` – Model performance metrics
- 📄 `bivariate_predictions.csv` – Actual vs Predicted CPI values
- 🖼️ `bivariate_regression_3d.png` – Visual plot of model surface

---

## 🗂 Project Structure

fuel_transport_regression_project_v2/
│
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ └── bivariate_regression.ipynb
├── output/
│ ├── metrics/
│ ├── plots/
│ └── results/
└── README.md


---

## ✅ Status: Phase 3 Complete

Model finalized, evaluated, and visualized. Project is ready for GitHub deployment and report generation.
