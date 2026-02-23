# Rain Prediction Project

Weather-based binary classification to predict whether it will rain (0 = No, 1 = Yes) using features like Temperature, Humidity, Wind Speed, Cloud Cover, and Pressure.

## Overview
- Dataset: 2500 synthetic weather samples
- Goal: Handle class imbalance and evaluate models beyond accuracy
- Models: Logistic Regression & Random Forest (baseline + SMOTE)
- Key learning: SMOTE significantly improves rain recall on imbalanced data
- Best model: Random Forest + SMOTE

## Tech Stack
- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- seaborn & matplotlib (EDA & visualizations)

## How to Run
1. Open in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Taimoor-Anjum/Rain-Prediction-Weather-ML/blob/main/Weather_Forecasting_Project_(3).ipynb)

2. Or clone locally:  
   ```bash
   git clone https://github.com/Taimoor-Anjum/Rain-Prediction-Weather-ML.git
