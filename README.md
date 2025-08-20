# French Bakery Demand Forecasting (Portfolio Project)

**Author:** Felicia Angel  
**Last Updated:** 2025  

This project applies **statistical time series forecasting** to daily bakery sales data (e.g., croissant, baguette, pain au chocolat). The goal is to showcase a **clean, reproducible workflow** that bridges **data science techniques** with **business insights**.

---

## Highlights
- Exploratory Data Analysis (EDA) to uncover demand patterns  
- Baseline models (Naïve, Seasonal-Naïve, Moving Average) for benchmarking  
- AutoARIMA and Seasonal ARIMA models with validation split  
- Residual diagnostics and error metrics (MAE, RMSE, MAPE)  
- Business-oriented conclusions to guide inventory & staffing decisions  
---
## Results & Insights

### Key Findings

* **Seasonality:** Strong **weekly cycles** — higher demand on weekends.
* **Best Models:** Seasonal Naïve is a strong baseline, but **SARIMA (7-day seasonality)** improves accuracy.
* **Forecast Accuracy:** Seasonal models reduce forecast error compared to non-seasonal ones.

### Business Impact

* **Inventory planning:** Increase croissant & baguette production by \~15–20% on weekends.
* **Staffing:** Add staff during weekend mornings to meet demand peaks.
* **Waste reduction:** Leaner weekday production minimizes unsold stock.

---

## 📌 Next Steps

* Add **holiday & promotion features** (SARIMAX with exogenous variables)
* Implement **rolling-origin backtesting** for robust evaluation
* Extend analysis across **all bakery products** in one loop, with a dashboard view
* Explore **ML-based models** (XGBoost, LSTMs) for comparison

---

## 🧑‍💻 Tech Stack

* Python 3.10+
* pandas, numpy, matplotlib
* statsmodels, scikit-learn
* statsforecast, utilsforecast, pmdarima

---
