# Threat Modeling and Forecasting

This repository demonstrates applied statistical modeling and machine learning techniques for analyzing and forecasting threat incidents relevant to national security. It combines synthetic simulations with real-world datasets, including the Global Terrorism Database (GTD), to explore Poisson regression, time-series forecasting, spatial-temporal panel modeling, clustering, and geospatial visualization. Designed as a developmental portfolio, this project reflects a growing technical fluency in predictive analytics for mission-critical applications.

## 🔍 Notebooks Included

- `01_poisson_regression_threat_counts.ipynb`  
  Simulates threat incident counts and models them using Poisson regression.

- `02_time_series_forecasting_incidents.ipynb`  
  Uses ARIMA and exponential smoothing to forecast future incident trends.

- `03_spatial_temporal_panel_model.ipynb`  
  Creates synthetic spatial-temporal panel data and applies regression to analyze geographic and temporal threat patterns.

- `04_predictive_model_summary.ipynb`  
  Compares models and evaluates predictive accuracy for different threat types.

- `05_explore_enhanced_threat_data.ipynb`  
  Explores proximity scores, signal strength, and threat types in enriched synthetic data.

- `06_threat_clustering_enhanced_data.ipynb`  
  Uses KMeans and PCA to cluster threats by proximity, signal, and geography.

- `07_gtd_us_threat_analysis.ipynb`  
  Analyzes U.S. incidents (2010–2019) from the Global Terrorism Database with geospatial and casualty breakdowns.

## 📦 Requirements

See `requirements.txt` for exact versions. Key Python packages include:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `geopandas` *(for future geospatial work)*

## ⚠️ Disclaimer

All synthetic datasets are generated for demonstration purposes only.  
No sensitive or classified information is used in this repository.

