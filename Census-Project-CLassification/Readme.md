Census Income Prediction Project

This project focuses on predicting income levels based on census data using various machine learning algorithms including logistic regression, decision tree, random forest, K-nearest neighbors (KNN), and Naive Bayes. The goal is to analyze the census income dataset and build models to predict whether an individual's income exceeds $50K per year.
Objective

The primary objective of this project is to implement and compare different machine learning algorithms for income prediction based on census data. Specifically, we aim to:

    Explore and preprocess the census income dataset.
    Implement logistic regression, decision tree, random forest, KNN, and Naive Bayes algorithms for income prediction.
    Perform feature engineering to extract relevant predictors and enhance model performance.
    Apply hyperparameter tuning and selection techniques to optimize each algorithm's performance.
    Evaluate and compare the performance of different models based on accuracy and other relevant metrics.

Dataset

The dataset used for this project is the Census Income dataset (also known as "Adult" dataset) from the UCI Machine Learning Repository. It contains various attributes including age, education, occupation, marital status, race, gender, hours per week worked, and more.

    Dataset Link: UCI Machine Learning Repository - Census Income Dataset

Project Structure

The project is organized into the following directories and files:

    data/: Contains the census income dataset (adult.csv) and any additional data used for analysis.

    notebooks/: Jupyter notebooks for data preprocessing, exploratory data analysis (EDA), feature engineering, model implementation, hyperparameter tuning, and model evaluation.

    scripts/: Python scripts for feature engineering, hyperparameter tuning, and model training.

    models/: Saved trained models after hyperparameter tuning.

    README.md: Project overview and instructions (this file).

Setup and Usage

    Clone the Repository:

    bash

git clone https://github.com/your-username/census-income-prediction.git
cd census-income-prediction

Setup Python Environment:

    It's recommended to use a virtual environment for this project.

bash

    # Create a virtual environment (optional but recommended)
    python3 -m venv venv
    source venv/bin/activate  # Activate the virtual environment (Linux/Mac)
    # or
    .\venv\Scripts\activate  # Activate the virtual environment (Windows)

    # Install required packages
    pip install -r requirements.txt

    Explore Notebooks:
        Navigate to the notebooks/ directory to run and explore Jupyter notebooks for data preprocessing, model implementation, and evaluation.

    Run Scripts:
        Execute Python scripts in the scripts/ directory for feature engineering, hyperparameter tuning, and model training.

    Model Evaluation:
        Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
        Compare and analyze the results of different algorithms.

References

    UCI Machine Learning Repository - Census Income Dataset
    Scikit-learn Documentation - Machine Learning Algorithms
