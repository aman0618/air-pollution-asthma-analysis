# Air Pollution and Asthma Analysis

## Overview

This repository contains the code and analysis for the research project:

**Asthma and Air Pollution: A Computational Study of PM2.5 Exposure and Digital Health-Seeking Behavior**  
(manuscript ready for submission)

The goal of this project is to investigate how daily air pollution (PM2.5) relates to asthma-related health-seeking behavior as observed through web signals.

---

## Motivation

Respiratory conditions like asthma are strongly influenced by air quality. Traditional epidemiological studies measure clinical outcomes, but digital epidemiology enables us to observe behavioral responses through online search patterns.

This project:
- Aligns pollution exposure time series with health-seeking search behavior
- Explores lagged responses
- Applies machine learning models to understand patterns

This analysis contributes to human-centered environmental data science and responsible AI for public health.

---

## Data

### Sources

1. **Air Pollution Data (PM2.5)**  
   - Source: (Add actual source — e.g., CPCB / OpenAQ / EPA)

2. **Google Trends / Search Behavior**
   - Search terms: asthma, wheezing, inhaler, etc.
   - Weekly search interest
   - Source: Google Trends

---

## Methodology

The analysis workflow includes:

1. **Time Alignment**
   - Convert daily PM2.5 to weekly aggregates
   - Align with Google Trends weekly data

2. **Feature Engineering**
   - Create lagged variables
   - Rolling averages

3. **Modeling**
   - Regression
   - Random Forest, Gradient Boosting, XGBoost

4. **Evaluation**
   - R², RMSE
   - Feature importance

---

## Results Summary

- Tree-based models tend to outperform linear regression.
- Lagged pollution features help identify delayed behavioral responses.

---

## Notebooks

- `data_preprocessing.ipynb`
- `feature_engineering.ipynb`
- `modeling.ipynb`
- `results_analysis.ipynb`

---

## Usage Instructions

```bash
git clone https://github.com/aman0618/air-pollution-asthma-analysis.git
cd air-pollution-asthma-analysis
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
