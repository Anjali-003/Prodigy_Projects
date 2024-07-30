# Prodigy Internship Task 1

This repository contains the implementation of a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms. 

## Implementation
1. Import Libraries: Imported libraries for data manipulation, model training, evaluation, and visualization.
2. Load Data: Read the datasets from CSV files named train.csv and test.csv.
3. Inspect Data: Print columns and info of the datasets to understand their structure and contents.
4. Drop Irrelevant Features: Removed columns that are not relevant to the prediction task.
5. Handle Missing Values: Identify and assign missing values in dataset using the mean strategy.
6. Visualize Data: Ploted histograms, distribution plots, and boxplots to understand the distribution and outliers in the data.
7. Correlation Analysis: Ploted the correlation matrix to identify features with low correlation to the target variable and droped them.
8. Split Data: Separated the target variable (SalePrice) from the features in the training dataset.
9. Normalize Data: Normalized the feature values using StandardScaler.
10. Train Linear Regression Model: Trained linear regression model on the training data and evaluate it using cross-validation.
11. Train Ridge Regression Model: Used GridSearchCV to find the best hyperparameters for the Ridge regression model, trained it, and evaluated its performance.
12. Train Lasso Regression Model: Used GridSearchCV to find the best hyperparameters for the Lasso regression model, trained it, and evaluated its performance.
13. Train ElasticNet Regression Model: Used GridSearchCV to find the best hyperparameters for the ElasticNet regression model, trained it, and evaluated its performance.
14. Calculate RMSE: Computed the Root Mean Squared Error (RMSE) for all trained models to compare their performance.
15. Make Predictions: Used the best-performing model to predict house prices on the test dataset.
16. Save Predictions: Created a DataFrame with the predicted house prices and save it.

### Link of the dataset

Dataset : - https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data



