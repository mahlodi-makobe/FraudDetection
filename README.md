# Fraud Detection Project

## Overview
This project focuses on building a machine learning model to detect fraudulent transactions using a synthetic financial transactions dataset. The model is trained using XGBoost and achieves high accuracy in distinguishing between fraudulent and non-fraudulent transactions.

## Dataset
The dataset used in this project is a synthetic financial transactions dataset containing 50,000 rows and 21 features. It includes numerical, categorical, and temporal data, with a binary target variable (`Fraud_Label`).

## Key Steps
1. **Data Exploration**: Analyzed the dataset to understand its structure and distribution.
2. **Data Preprocessing**: Handled categorical variables, created new features, and split the data into training and testing sets.
3. **Model Building**: Trained an XGBoost classifier and evaluated its performance.
4. **Feature Importance**: Analyzed the most influential features for fraud detection.
5. **Prediction**: Prepared new data and used the trained model to predict fraud labels.

## Results
The model achieved a **ROC-AUC score of 1.0000**, demonstrating perfect discrimination between fraudulent and non-fraudulent transactions.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-project.git
