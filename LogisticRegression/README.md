# Diabetes Data Analysis

## Overview

This project involves analyzing and building classification models to predict whether a person has diabetes based on various health-related features. The models used in this project include:

- **Logistic Regression**

In addition to classification, **Hyperparameter Tuning** was performed using **GridSearchCV** to find the best set of parameters for each model. The dataset was preprocessed, and various machine learning models were trained and evaluated to determine their effectiveness in predicting diabetes.

## Dataset

The dataset used in this project contains health-related data such as age, glucose levels, BMI, etc., and the target variable is whether the person has diabetes or not (binary classification: 0 = No, 1 = Yes). The dataset includes features such as:

- `Pregnancies`: Number of pregnancies
- `Glucose`: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg / height in m²)
- `DiabetesPedigreeFunction`: A function that scores the likelihood of diabetes based on family history
- `Age`: Age of the patient
- `Outcome`: Whether the patient has diabetes (1 = Yes, 0 = No)

This dataset is included in this repository as a `.csv` file and can be accessed for analysis.

## Technologies Used

- **Python**: Programming language used for data analysis and machine learning
- **Pandas**: For data manipulation and preprocessing
- **Scikit-learn**: For machine learning models, hyperparameter tuning, and evaluation
- **Matplotlib** and **Seaborn**: For visualizations
- **NumPy**: For numerical operations

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ArigalaAdarsh/ML.git
cd LogisticRegression
 
