## Credit Card Fraud Detection

This repository contains a Jupyter Notebook for detecting credit card fraud using machine learning techniques. The dataset used for this analysis is the [Credit Card Fraud Detection dataset]([https://www.kaggle.com/mlg-ulb/creditcardfraud]) from Kaggle. 

## Overview

Credit card fraud detection is a critical task in the financial sector to prevent unauthorized transactions. This project demonstrates how to build and evaluate a machine learning model to identify fraudulent transactions.

## Dataset

The dataset consists of transactions made by credit cards in September 2013 by European cardholders. It contains 284,807 transactions, including 492 fraudulent transactions. The dataset includes features such as transaction time, amount, and anonymized principal components obtained using PCA.

## Project Steps

### 1. Data Loading
The dataset is loaded and examined to understand its structure and basic statistics.

### 2. Data Exploration
Initial exploration is performed to get insights into the data distribution and detect any anomalies or missing values.

### 3. Data Preprocessing
Data preprocessing includes scaling features, handling imbalanced data, and splitting the dataset into training and testing sets.

### 4. Model Training
A Random Forest model is trained to classify transactions as fraudulent or non-fraudulent.

### 5. Model Evaluation
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score.

## How to Use

1. Clone the repository.
2. Download the dataset from Kaggle and place it in the project directory.
3. Install the required libraries (`pandas`, `numpy`, `scikit-learn`).
4. Open and run the Jupyter Notebook.

## Conclusion

This project provides a framework for detecting credit card fraud using logistic regression. The notebook can be further extended by exploring different machine learning algorithms and tuning hyperparameters to improve performance.

## Acknowledgements

- Dataset provided by [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).
