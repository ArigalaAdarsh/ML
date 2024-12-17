# Us Housing Price Prediction Project

## Overview

This project aims to predict the median house value based on various features of the housing data. The dataset includes information such as the geographical location, number of rooms, household income, and more. Regression models **Linear Regression**  are used to predict the median house value in a specific region.

## Dataset

The dataset consists of multiple columns describing various characteristics of housing units and the surrounding area. The columns in the dataset are:

- `Longitude`: The longitude coordinate of the housing location.
- `Latitude`: The latitude coordinate of the housing location.
- `Housing Median Age`: The median age of houses in a specific area. This is the middle value of the age of housing units in years.
- `Total Rooms`: The total number of rooms in a particular housing unit.
- `Total Bedrooms`: The total number of bedrooms in a housing unit.
- `Population`: The number of people living in a specific housing area.
- `Households`: The number of households (families or groups living together) in a specific area.
- `Median Income`: The median income of households in the area, represented in tens of thousands of dollars (e.g., a value of 3 represents an income of $30,000).
- `Median House Value`: The median value of owner-occupied houses in the area. This column is the target variable and represents the value that we are trying to predict.
- `Ocean Proximity`: A categorical column indicating the proximity of the housing unit to the ocean. It can have values like "near bay," "near ocean," "inland," etc.

## Technologies Used

- **Python**: Programming language used for data analysis and machine learning
- **Pandas**: For data manipulation and preprocessing
- **Scikit-learn**: For implementing machine learning models such as Linear Regression and Random Forest Regression
- **Matplotlib** and **Seaborn**: For visualizations
- **NumPy**: For numerical operations

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ArigalaAdarsh/ML.git
cd LinearRegression
 
