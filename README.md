# Module 3 Final Project readme

In this project we will build a classification model to predict whether or not a customer will churn, or stop doing business with SyriaTel, a mobile network provider.  We will explore, clean and feature engineer our dataset and iteratively model our data using and tuning machine learning algorithms to build a classifier suited for the best predictions for the business problem at hand.

## Goals

* Interpret our data, feature engineer and scale as necessary to create the best possible framework for modeling
* Visualize some of the most important features, understand the business problem and use our classifier as a baseline for tangible solutions
* Iterate through several models and parameters with a focus on recall, minimizing false negatives as best as our models are able

## Methodologies

* Identify predictor variables and visualize relationships to target variable ('churn')
* Create baseline model using Random Forest Classifier, Pipeline, and GridSearchCV, adjust parameters to maximize recall score
* Iterate through Logistic Regression, Gradient Boosting, AdaBoost, and K-Nearest Neighbors models, adjusting fits and scaling data where necessary
* Create dummy variables for comparitive modeling on best-performing models
* Build two comparable well-performing models using Random Forest and Gradient Boosting classifiers
* Identify most important features from final model