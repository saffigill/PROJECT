# Airbnb Price Prediction Project

## Project Overview

This project aims to predict Airbnb listing prices using machine learning techniques. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and model building.

## Data Cleaning

The data cleaning process involved:

*   Dropping unnecessary columns.
*   Handling missing values by filling them with the mean for numerical columns and the mode for categorical columns.
*   Converting column names to lowercase and replacing spaces with underscores.
*   Removing dollar signs and commas from price columns.
*   Removing duplicate rows.

## Exploratory Data Analysis (EDA)

The EDA included:

*   Analyzing the distribution of listings by neighborhood.
*   Visualizing listings on a map using geographical data.
*   Examining the distribution of property types and room types.
*   Analyzing the distribution of review scores.
*   Analyzing the distribution of prices and minimum nights.

## Feature Engineering

The feature engineering steps included:

*   Applying log transformations to reduce skewness in price, minimum\_nights, accommodates, and number\_of\_reviews.
*   Handling missing values in bathrooms, bedrooms, and beds by filling them with 0.
*   Applying ordinal encoding to categorical columns.
*   Applying robust scaling to numerical columns.

## Modeling

The following machine learning models were used to predict Airbnb listing prices:

*   Random Forest Regressor
*   Gradient Boosting Regressor
*   Linear Regression
*   Decision Tree Regressor

The models were evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R2), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).

## Conclusion

The project provides insights into the factors influencing Airbnb listing prices and demonstrates the application of machine learning techniques for price prediction.
