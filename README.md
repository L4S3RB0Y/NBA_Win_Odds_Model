# NBA_Win_Odds_Model

# Predicting NBA Game Outcomes: A Machine Learning Approach
Jun Ze He, Eduard Bueno, Brian Mualim, Anthony Ko, Theresa Unsulangi, Chloe Guo

## Project Overview
This project explores the predictive modeling of NBA game outcomes using statistical and machine learning techniques. Utilizing data from the 2023-2024 NBA season, our goal was to determine the most effective model for predicting game results based on key performance metrics.

## Data & Methodology
Our dataset included a variety of game statistics such as points scored, field goal percentage, turnovers, and rebounds. To enhance predictive performance, we engineered new features, including pre-game performance differentials and historical matchup records. After preprocessing and feature selection, we trained three machine learning models:

## Logistic Regression (with L1 regularization)
Random Forest Classifier
XGBoost Classifier
We optimized these models using forward stepwise feature selection, hyperparameter tuning via grid search, and dimensionality reduction through Principal Component Analysis (PCA).

## Key Findings
Among the models tested, logistic regression with PCA-transformed features performed best, achieving an accuracy of 68.55%, while XGBoost performed the worst at 67.39%. Logistic regression was favored for its interpretability and superior performance on this dataset, especially given its robustness against overfitting.

## Conclusion & Future Work
Our study demonstrates the effectiveness of statistical and machine learning methods in sports analytics. Future improvements could include expanding the dataset to incorporate more seasons, integrating player-level statistics, and experimenting with deep learning models to capture more complex relationships.
