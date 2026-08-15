# E-commerce-cyber-risk-analysis-and-assessment-
A hybrid e-commerce cyber risk assessment framework using Jumia’s publicly disclosed cybersecurity data, Logistic Regression for risk prediction, and Annual Loss Expectancy (ALE) for financial risk estimation. Includes dataset preprocessing, model evaluation, visualizations, and reproducible Python implementation.

## Overview

This project presents a data-driven cyber risk analysis and assessment framework for e-commerce environments, using publicly disclosed cybersecurity and operational risk information from Jumia Technologies AG.

The project combines qualitative risk assessment, quantitative financial risk modelling, numerical analysis, and machine learning-based predictive analytics to evaluate cyber risk and estimate potential financial exposure.

## Key Components

- Qualitative analysis of publicly disclosed cybersecurity and operational risks
- Structured cyber risk dataset development
- Risk feature encoding and preprocessing
- Logistic Regression for cyber incident probability prediction
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Fraud/cyber incident probability visualization
- Annual Loss Expectancy (ALE) financial risk estimation
- Integration of machine learning probability with financial risk modelling

## Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Methodology

The framework follows an integrated risk assessment pipeline:

Public Disclosures
        ↓
Risk Identification
        ↓
Data Encoding & Preprocessing
        ↓
Logistic Regression
        ↓
Cyber Incident Probability
        ↓
ALE Financial Risk Estimation
        ↓
Risk Analysis & Visualization

## Dataset

The dataset was constructed from publicly available Jumia financial, operational, and cybersecurity disclosures covering the study period.

Risk indicators were converted into numerical variables suitable for supervised machine learning.

## Model

Logistic Regression was selected because it is appropriate for binary classification and produces interpretable probability estimates.

The resulting probability values are subsequently used as an input to the quantitative financial risk model.

## Results

The implemented model produced:

- Accuracy: 66.7%
- Precision: 0.67
- Recall: 1.00
- F1-Score: 0.80

The system also generated probability outputs for individual risk observations and demonstrated how these probabilities can be incorporated into Annual Loss Expectancy calculations.
