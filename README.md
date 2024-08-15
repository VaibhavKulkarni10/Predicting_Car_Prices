# Car Price Prediction Project

This project aims to predict car prices using various regression algorithms, including Linear Regression, Decision Trees, KNN Regressor, etc. Predictive modeling involves multiple steps beyond building and fitting a model. Here, we document the entire process, from data collection and preprocessing to model evaluation.

## Project Overview
* *Dataset Selection*:
  * Selected a dataset from a predictive modeling competition, considering current car market trends.

* Data Preprocessing:
  * Checked the data types of each variable.
  * Identified and handled missing values and outliers.
  * Dropped unnecessary or redundant data.
  * Finalized the columns to be used for modeling.

* Data Visualization:
  * Used various plots (barplot, boxplot, histogram, etc.) to understand data insights.
  * Analyzed trends such as the price hike starting from the year 2000 and the demand for Jeep cars.
  * Examined the impact of amenities on car production.

* Further Preprocessing:
  * Applied one-hot encoding to transform categorical data into numerical format.
  * Scaled the data for uniformity.
  * Split the data into training and testing subsets.

* Feature Selection:
  * Used feature selection methods to choose the top ten features for modeling.
  
* Model Training and Evaluation:
  * Selected multiple regression algorithms.
  * Trained models using training data and tested them with testing data.
  * Predicted car prices and compared them with actual prices.
  * Evaluated models using graphs to identify patterns and performance scores.

* Model Comparison:
  * Performed t-tests using cross-validation with the neg_mean_squared_error metric.
  * Used evaluation metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
  * Compiled results into a table for easy comparison and identification of the best model.

