# Model Card

This document will summarize the models built for forecasting synthetic threat data.

# 📄 Model Card: Threat Forecasting Models

## Overview
This repository contains statistical modeling demonstrations built using synthetic threat incident data to simulate intelligence-driven forecasting scenarios. Models were designed to explore techniques like Poisson regression, ARIMA time-series forecasting, Exponential Smoothing, and spatial-temporal panel data analysis using Python.

---

## Intended Use
- Educational and developmental use by analysts transitioning into data science roles
- Demonstration of practical statistical modeling approaches for intelligence or national security use cases
- Framework for expanding into real-world classified or semi-structured threat data (e.g., SIGINT, HUMINT fusion)

---

## Models & Techniques Used
| Notebook | Model Type | Purpose |
|----------|------------|---------|
| 01 | Poisson Regression | Predict count-based threat incidents across categories |
| 02 | Exponential Smoothing & ARIMA | Time-based threat forecasting |
| 03 | OLS Panel Regression | Spatial-temporal modeling with categorical controls |
| 04 | Model Comparison | Evaluate MSE/MAE across multiple models |

---

## Ethical Considerations
- All data is **synthetic** and designed solely for demonstration purposes.
- No sensitive or classified data is used.
- Models are not intended for operational deployment without validation.

---

## Limitations
- Simplified modeling assumptions (e.g., linear effects, static features)
- No hyperparameter tuning or external validation performed
- Geolocation and advanced NLP elements are not included

---

## Author
Michael McKeever  
GitHub: [MLM2](https://github.com/MLM2)  
Email: mike.l.mckeever@gmail.com  
