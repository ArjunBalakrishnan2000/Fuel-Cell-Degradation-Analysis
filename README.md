# Fuel-Cell-Degradation-Analysis
Machine learning pipeline for predictive maintenance and voltage degradation analysis in PEM fuel cells using Gradient Boosting
## Project Overview
This project provides a robust, data-driven approach to predicting fuel cell voltage degradation using sensor telemetry. The objective is to identify key physical drivers of decay and minimize predictive error in long-term performance forecasting.

## Methodology
- **Preprocessing:** Implemented time-series downsampling to mitigate high-frequency signal noise.
- **Modeling:** Benchmarked Ensemble learning techniques, specifically Random Forest and Gradient Boosting Regressors.
- **Optimization:** Utilized GridSearchCV with 5-fold cross-validation to tune hyperparameters (Learning Rate, Tree Depth, Estimators).

## Key Results
- **Final Model:** Gradient Boosting Regressor
- **Performance:** RMSE of 0.0017V
- **Performance Gain:** Improvement over baseline Random Forest.

## Technical Stack
- Python 3.x
- Pandas/NumPy (Data manipulation)
- Scikit-Learn (Modeling & Scaling)
- Matplotlib/Seaborn (Visualization)
