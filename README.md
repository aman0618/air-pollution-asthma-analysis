# PM2.5 and Asthma Trend Prediction using Machine Learning

##  Overview
This project investigates the relationship between PM2.5 air pollution and asthma-related behavioral trends using machine learning and time-series analysis.

This work supports a research manuscript submitted to *SN Computer Science (Springer Nature)*.

---

##  Problem Statement
Can PM2.5 alone predict asthma-related trends?

---

##  Key Findings
- PM2.5 alone is a **very weak predictor** (R² < 0.01)
- Incorporating **lagged, seasonal, and environmental features** significantly improves performance
- **Random Forest achieved best performance (R² ≈ 0.61)**

This shows asthma trends are influenced by **multiple interacting factors**, not pollution alone.

---

##  Methods Used
- Linear Regression
- Random Forest
- Gradient Boosting
- XGBoost
- Prophet (Time-Series Forecasting)

---

##  Results Summary

| Model                  | R² Score |
|-----------------------|--------|
| Linear Regression     | < 0.01 |
| With Feature Engg     | ~0.49  |
| Random Forest         | ~0.61  |
| Gradient Boosting     | ~0.58  |
| XGBoost               | ~0.26  |

---
##  Project Structure
air-pollution-asthma-analysis/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks
├── src/ # Core scripts (models, preprocessing)
├── results/ # Graphs and outputs
└── README.md


---

## 📈 Key Insights
- Environmental health modeling requires **multi-factor analysis**
- Feature engineering (lags, seasonality) is critical
- Ensemble models outperform linear models in complex systems

---

## 🔁 Reproducibility
To run the project:
1. Clone the repository
2. Install dependencies
3. Run notebooks in order

---

## 📜 License
For academic and research use only
