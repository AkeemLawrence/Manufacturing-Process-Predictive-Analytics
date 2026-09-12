# Manufacturing Process Predictive Analytics

Predictive analytics and machine learning project examining the factors that influence pH during a beverage manufacturing process.

## Project Overview

Maintaining consistent pH is important to beverage quality, stability, safety, and regulatory compliance. This project analyzes historical manufacturing data to identify production variables associated with pH and develop a predictive model capable of estimating pH from process inputs.

The dataset contains **2,571 production observations and 33 variables** representing manufacturing conditions including pressure, temperature, fluid flow, chemical composition, machine settings, and product brand.

## Objectives

- Explore and clean manufacturing process data
- Identify variables associated with changes in pH
- Evaluate missing values, distributions, outliers, and correlations
- Compare multiple regression and machine-learning approaches
- Develop a model for predicting pH from manufacturing inputs
- Translate modeling results into operational recommendations

## Methods

The analysis was conducted in **R** and included:

- Exploratory Data Analysis (EDA)
- Missing-value analysis and k-Nearest Neighbors (kNN) imputation
- Outlier and distribution analysis
- Correlation analysis
- Data preprocessing
- Model training and evaluation
- Cross-validation and hyperparameter tuning

Models evaluated included:

- Linear Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- MARS
- Cubist

## Model Results

After model comparison and tuning, **Cubist** produced the strongest performance on the held-out test data.

| Metric | Result |
|---|---:|
| RMSE | 0.093 |
| R² | 0.717 |
| MAE | 0.060 |

The analysis also identified manufacturing variables associated with pH behavior and highlighted opportunities for improved process monitoring and quality control.

## Business Application

A predictive pH model could potentially be incorporated into a manufacturing monitoring system or dashboard, allowing production teams to identify conditions associated with pH deviations and improve process control.

Potential extensions include:

- Real-time pH prediction
- Production quality dashboards
- Model monitoring
- Brand-specific modeling
- Additional feature engineering and model tuning
- Cloud-based analytics and model deployment

## Technologies

- R
- RStudio
- dplyr / tidyverse
- ggplot2
- caret
- Cubist
- Random Forest
- XGBoost
- SVM
- MARS
- kNN imputation
- Statistical modeling
- Data visualization

## Project Files

This repository contains the technical analysis, predictive modeling workflow, visualizations, model evaluation results, and accompanying business report.

## Contributors

This project was completed collaboratively as part of graduate Data Science coursework at CUNY.

**Contributors:**  
Warner Alexis · Dirk Hartog · Amish Rasheed · Woodelyne Durosier · Akeem Lawrence · Fares Alahdab

## Author

**Akeem Lawrence**  
M.S. Data Science — CUNY  
Google Cloud + Data & AI | Python/Colab | RStudio | BigQuery SQL | Gemini Enterprise
