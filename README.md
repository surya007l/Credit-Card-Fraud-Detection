# Credit Card Fraud Detection
A machine learning-based solution to detect fraudulent credit card transactions using a real-world anonymised credit card data dataset. This project explores various supervised classification algorithms to identify fraudulent activities accurately.

📌 Table of Contents
Overview

Dataset

Technologies Used

Project Structure

Model Performance

Installation

Usage

Future Work

Contributing

License

📖 Overview
Credit card fraud is a serious issue that results in billions of dollars of losses annually. This project uses machine learning to classify transactions as fraudulent or legitimate. Since fraud cases are extremely rare, the dataset is highly imbalanced, and careful techniques are used to handle this.

The objective is to:

Detect fraudulent transactions.

Improve model performance using data preprocessing and feature engineering.

Use evaluation metrics suited for imbalanced datasets.

📊 Dataset
The dataset used is the Credit Card Fraud Detection dataset available on Kaggle. It contains transactions made by European cardholders in September 2013.

Total Transactions: 284,807

Fraudulent Transactions: 492 (0.172%)

Features: 30 (anonymized for privacy; includes PCA components V1-V28, Time, Amount, and Class)

🛠 Technologies Used
Python

Pandas, NumPy (Data Processing)

Scikit-learn (Modelling & Evaluation)

Matplotlib, Seaborn (Visualization)

Jupyter Notebook / Google Colab

🧠 Model Performance
After evaluating multiple models (Logistic Regression, Random Forest, XGBoost, etc.), the following metrics were considered:

Precision

Recall

F1-Score

ROC-AUC Score

Confusion Matrix

Best Performing Model: Random Forest

Accuracy: 0.9996

Precision: 0.9873

Recall: 0.7959

F1 Score: 0.8814

Matthews Correlation Coefficient (MCC): 0.8863

