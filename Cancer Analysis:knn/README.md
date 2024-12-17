# Cancer Analysis: KNN using the Cancer Dataset

## Overview

In this project, I performed **cancer diagnosis classification** using the **K-Nearest Neighbors (KNN)** algorithm. The dataset contains various features derived from images of breast cancer cell nuclei, and the goal is to predict whether a tumor is malignant or benign based on these features.

The analysis involves data preprocessing, feature selection, and applying the KNN algorithm for classification.

## Dataset

The dataset used in this project is the **cancer dataset**, which includes the following columns:

- `id`: Unique identifier for each sample
- `diagnosis`: Diagnosis of the tumor (M = malignant, B = benign)
- `radius_mean`: Mean radius of the tumor
- `texture_mean`: Mean texture of the tumor
- `perimeter_mean`: Mean perimeter of the tumor
- `area_mean`: Mean area of the tumor
- `smoothness_mean`: Mean smoothness of the tumor
- `compactness_mean`: Mean compactness of the tumor
- `concavity_mean`: Mean concavity of the tumor
- `concave points_mean`: Mean concave points of the tumor
- `symmetry_mean`: Mean symmetry of the tumor
- `fractal_dimension_mean`: Mean fractal dimension of the tumor
- `radius_se`: Standard error of radius
- `texture_se`: Standard error of texture
- `perimeter_se`: Standard error of perimeter
- `area_se`: Standard error of area
- `smoothness_se`: Standard error of smoothness
- `compactness_se`: Standard error of compactness
- `concavity_se`: Standard error of concavity
- `concave points_se`: Standard error of concave points
- `symmetry_se`: Standard error of symmetry
- `fractal_dimension_se`: Standard error of fractal dimension
- `radius_worst`: Worst-case radius of the tumor
- `texture_worst`: Worst-case texture of the tumor
- `perimeter_worst`: Worst-case perimeter of the tumor
- `area_worst`: Worst-case area of the tumor
- `smoothness_worst`: Worst-case smoothness of the tumor
- `compactness_worst`: Worst-case compactness of the tumor
- `concavity_worst`: Worst-case concavity of the tumor
- `concave points_worst`: Worst-case concave points of the tumor
- `symmetry_worst`: Worst-case symmetry of the tumor
- `fractal_dimension_worst`: Worst-case fractal dimension of the tumor
- `Unnamed: 32`: Unnamed column (can be dropped)

This dataset is included in this repository as a `.csv` file and can be accessed for analysis.

## Technologies Used

- **Python**: Programming language used for data analysis and machine learning
- **Pandas**: For data manipulation and preprocessing
- **Scikit-learn**: For implementing the KNN algorithm
- **Matplotlib** and **Seaborn**: For visualizations
- **NumPy**: For numerical operations

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ArigalaAdarsh/ML.git
cd Cancer-Analysis-KNN
 
