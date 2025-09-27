# House price prediction with Linear Regression and Random Forest

Table of Contents:-

Introduction
Problem Statement
Introduction to Random Forest
Assumptions of Random Forest
Results
Conclusion

Introduction:-

Predicting house prices is a critical task in the real estate sector, financial planning, and investment analysis.The aim of this project is to predict house prices using one basic machine learning algorithm, Linear Regression, and one advanced algorithm, Random Forest Regressor. We will also use Grid search Cross Validation for hyperparameter tuning.

The California Housing Prices datasets can be downloaded here: https://www.kaggle.com/datasets/camnugent/california-housing-prices .

Random Forest was found to be the better model for predicting house prices. It out performed the Linear regession algorithms with performance accuracy of 82% using gridseachCV. The most important predictor was the Median_income.

This project is a first pass to get us quickly to a reasonable good model prototype.

Problem Statement:-

The objective is to build a machine learning model to predict house prices based on historical data. Accurate prediction models are essential for:

Helping buyers and sellers make informed decisions.
Assisting banks in mortgage approvals.
Supporting real estate businesses in market analysis.

Introduction to Random Forest:-

Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting. Each tree is trained on a random subset of the data and features, making the model highly robust and generalizable.

Key characteristics:
Works well with both categorical and numerical data.
Handles missing values effectively.
Reduces variance by averaging multiple decision trees.
Provides feature importance for better interpretability.

Assumptions of Random Forest:-

Independence of trees – Each decision tree is trained independently.
Bootstrap sampling – Data subsets drawn with replacement provide diversity.
Feature randomness – At each split, a random subset of features is chosen.
Sufficient data – Works best with large datasets to capture variability.

Result and conclusions:-

The Random Forest model achieved strong predictive accuracy compared to baseline models (82%).
It provided insights into the most important features influencing house prices (e.g., Income, location, number of bedrooms, etc.).
The model effectively reduced overfitting and generalized well on test data.

Overall, Random Forest proved to be a reliable method for real-world price prediction tasks.
