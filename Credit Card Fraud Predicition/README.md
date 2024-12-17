# Credit Card Fraud Prediction

## Overview

In this project, we aim to predict credit card fraud using a dataset that contains transaction data, where the objective is to classify transactions as fraudulent or non-fraudulent. This problem is approached as a binary classification task using machine learning techniques.

We perform data preprocessing, exploratory data analysis (EDA), and then apply the **Random Forest Classifier** to predict the likelihood of a fraud. The performance of the model is evaluated using common classification metrics such as accuracy, precision, recall, and F1 score.

## Dataset

The dataset used in this project can be found [here on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The dataset consists of credit card transactions made by European cardholders in September 2013. It includes both **fraudulent** and **non-fraudulent** transactions.

Key columns in the dataset:

- `Time`: Time elapsed since the first transaction in seconds.
- `V1, V2, ..., V28`: Anonymized features resulting from PCA transformation. These features are used for fraud detection.
- `Amount`: The amount of the transaction.
- `Class`: The target variable indicating whether the transaction was fraudulent (`1`) or not (`0`).

The dataset is highly imbalanced, with the number of fraudulent transactions being significantly lower than the non-fraudulent transactions.

## Technologies Used

- **Python**: Programming language used for data analysis and machine learning.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For visualizations.
- **Scikit-learn**: For machine learning models and evaluation metrics.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ArigalaAdarsh/ML.git
cd Credit-Card-Fraud-Prediction
 
