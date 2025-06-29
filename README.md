# House Price Prediction in Beijing – UNED Data Mining Project (2024)

This repository contains the full solution to the self-assessment for Module 5 – Data Mining I, from the Master's in Big Data and Data Science Applied to Economics and Business at UNED (2024–2025).

## 🎯 Objective

To implement a predictive modeling pipeline to estimate the total price (`totalPrice`) of residential properties in Beijing using real 2017 housing market data. The project involves thorough data preprocessing, training of various machine learning algorithms, and selection of the optimal model based on accuracy and explainability.

## 🧾 Dataset Overview

The dataset includes housing-related features such as:
- Property size, rooms, and amenities
- Building type, renovation status, and age
- Geolocation (longitude and latitude)
- Market-related metrics (days on market, followers)
- Proximity to subway, elevator availability
- Price per square meter and total price

Files used:
- `mercado_beijing_2017.csv` (housing market data)
- `beijing_map.RData` (map data for visualization)

## 📦 Project Stages

### 1. Data Preprocessing
- Missing value treatment and outlier detection
- Variable selection and transformation
- Feature engineering and encoding
- Exploratory analysis with visualizations and correlation matrices

### 2. Model Training and Evaluation
- Regression Trees (CART), Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machines (SVM)  
- Neural Networks (MLP)  
- Bagging, Boosting, Gradient Boosting  
- AutoML with H2O  
- Linear and Lasso Regression (optional)

Each model was evaluated using:
- RMSE, MAE, R² on training and test sets
- Execution time and generalization ability

### 3. Model Explainability
- Variable importance
- Partial Dependence Plots (PDP)
- SHAP-like interpretations with H2O
- Local interpretation of predictions

## 📊 Summary Results

A consolidated table compares all models based on evaluation metrics and interpretability. The model with the best trade-off between performance and transparency is selected and justified.

## 🛠️ Tools and Libraries

- R  
- `caret`, `tidymodels`, `h2o`, `ggplot2`, `reactable`, `DALEX`, `plumber`, `data.table`, `janitor`, `skimr`  
- RMarkdown for reproducible reporting

## 📁 Files Included

- `M05_AutoEv_Oscar Porta.html` – Final HTML report  
- `M05_AutoEv_Oscar Porta.Rmd` – Full source code in RMarkdown  

## 👨‍💻 Author

Óscar Porta  
Master’s Student in Big Data & Data Science – UNED  
GitHub: [Oscar-Porta](https://github.com/Oscar-Porta)
