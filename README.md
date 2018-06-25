# Titanic Survival Prediction

This repo is my work for the [Titanic Competition on Kaggle](https://www.kaggle.com/c/titanic). 

## Problem Description

The data used can be found at https://www.kaggle.com/c/titanic/data.
- **Training Data**: Passenger information (Name, Sex, Ticket, Cabin, Age, Class, etc) with binary labels. 
- **Test Data**: Same features as the training set but unlabeled
- **Goal**: To determine if the passsenger in the test set survived

## Pipeline

### Data Cleaning

- Completed the missing values.
- Extracted new features from existing ones, based on the observations made by feature pivoting and visualization.
- Dropped features that are mostly missing in the original datasets or have low uncorrelations with the survival rate.

### Machine Learning

- Randomly split the training set into two parts. One for training and the other for validation.
- Performed classification algorithms on the training part with Scikit-Learn library and verified the model on the validation part of the training set. 

| Algorithm | Hyperparameter | Score    |   |   |
|-----------|----------------|----------|---|---|
| KNN       | k = 20         |          |   |   |
|           |                |          |   |   |
|           |                |          |   |   |

- Predicted the survival on the test set with the trained model. 

