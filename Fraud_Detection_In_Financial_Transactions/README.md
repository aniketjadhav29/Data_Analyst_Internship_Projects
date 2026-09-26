# Fraud Detection in Financial Transactions

## Project Overview

This project identifies potentially fraudulent financial transactions using anomaly detection techniques.

## Dataset

Credit Card Fraud Detection Dataset.

The dataset contains highly imbalanced transaction data with fraudulent and legitimate transactions.

## Techniques Used

- Exploratory Data Analysis
- Class imbalance analysis
- Feature scaling
- Isolation Forest
- Autoencoder
- Fraud risk scoring
- Alert generation
- ROC-AUC
- PR-AUC
- Confusion Matrix

## Dataset Distribution

- Total transactions: 284,807
- Legitimate transactions: 284,315
- Fraudulent transactions: 492
- Fraud rate: 0.1727%

## Model Results

| Model | Precision | Recall | F1-Score | ROC-AUC | PR-AUC |
|---|---:|---:|---:|---:|---:|
| Isolation Forest | 3.91% | 83.67% | 7.46% | 95.39% | 17.17% |
| Autoencoder | 45.87% | 51.02% | 48.31% | 96.66% | 48.39% |

## Alert System

The project includes a fraud alert system using reconstruction error to classify transactions into:

- Low Risk
- Medium Risk
- High Risk
- Fraud Alert

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras
- Google Colab
- Machine Learning
- Anomaly Detection
