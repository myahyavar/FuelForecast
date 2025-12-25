# FuelForecast
fuel consumption prediction for trucks

1. Introduction
The goal of this work was to accurately predict fuel_consumption_sum for a large-scale
commercial vehicle telematics dataset provided in the course Kaggle competition. My
approach evolved through several stages:
1. Data exploration & preprocessing
2. Feature engineering (custom domain-inspired features)
3. Baseline CatBoost model
4. Parameter tuning & early stopping
5. Building a three-model ensemble (CatBoost + LightGBM + XGBoost)
6. Weights based on inverse-MAE and ridge regression
7. Model comparison on validation 
