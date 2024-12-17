# Census Income  Classification Project

## Overview

In this project, I performed **Exploratory Data Analysis (EDA)** and applied several **classification algorithms** to predict whether an individual earns more than $50,000 per year based on various demographic and employment features. The classification models used include:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**

Additionally, **Hyperparameter Tuning** was performed using **GridSearchCV** to optimize model performance, ensuring the best parameters for each model were selected for better predictive accuracy.

## Dataset

The dataset used in this project contains demographic information and income data. The following columns are included in the dataset:

- `age`: Age of the individual
- `workclass`: Type of employment (e.g., Private, Self-emp, Government)
- `fnlwgt`: Final weight (census weighting)
- `education`: Education level (e.g., Bachelors, Masters, PhD)
- `education-num`: Number of years of education
- `marital-status`: Marital status (e.g., Married, Single, Divorced)
- `occupation`: Type of occupation (e.g., Tech-support, Craft-repair)
- `relationship`: Relationship status (e.g., Husband, Wife, Own-child)
- `race`: Race (e.g., White, Black, Asian-Pac-Islander)
- `sex`: Gender (Male or Female)
- `capital-gain`: Capital gains income
- `capital-loss`: Capital losses
- `hours-per-week`: Weekly work hours
- `native-country`: Country of origin (e.g., United-States, Mexico, India)
- `Annual-Income`: Income label (<=50K or >50K) (Target variable)

This dataset is included in this repository as a `.csv` file and can be accessed for analysis.

## Technologies Used

- **Python**: Programming language used for data analysis and machine learning
- **Pandas**: For data manipulation and preprocessing
- **Scikit-learn**: For machine learning models, hyperparameter tuning, and evaluation
- **Matplotlib** and **Seaborn**: For visualizations
- **NumPy**: For numerical operations

### Used Algorithms

1. **Logistic Regression**: A linear model used for binary classification problems.
2. **Decision Tree Classifier**: A tree-based model that splits data into branches to classify instances.
3. **Random Forest Classifier**: An ensemble model using multiple decision trees for better accuracy.
4. **K-Nearest Neighbors (KNN)**: A non-parametric method for classification based on the proximity of data points.
  
### Hyperparameter Tuning
I used **GridSearchCV** for hyperparameter optimization to improve model performance. This method automatically performs an exhaustive search over specified parameter values for a model and finds the best combination based on cross-validation performance.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ArigalaAdarsh/ML.git
cd Census-Project-Classification
 
