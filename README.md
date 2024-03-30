# Logistic-Regression-Model
## Titanic Survival Prediction
## Overview
This project utilizes logistic regression to predict the survival of passengers aboard the Titanic based on various features such as age, gender, ticket class, and more. The sinking of the RMS Titanic is one of the most infamous shipwrecks in history, and this dataset serves as a classic machine learning problem to predict passenger survival.

## Dataset
The dataset used in this project is the famous Titanic dataset available on Kaggle. It contains information about passengers, including whether they survived or not, their socio-economic status, age, cabin, and other attributes. The dataset is split into a training set and a test set for model development and evaluation.

## Approach
Data Preprocessing: Initial data exploration and preprocessing were conducted to handle missing values, categorical variables, and feature engineering.

Feature Engineering: Relevant features were selected and engineered to improve the predictive power of the model. This included encoding categorical variables, creating new features, and scaling numerical features.

Model Training: Logistic Regression, a popular algorithm for binary classification, was chosen as the predictive model. The model was trained on the training dataset and tuned using cross-validation techniques.

Evaluation: The trained model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score on the test dataset. Additionally, a confusion matrix was analyzed to understand the model's performance in predicting survival and non-survival cases.

Deployment: The trained model can be used to predict the survival probability of passengers given their characteristics.

## Requirements
Python 3.x
Jupyter Notebook or any Python IDE
Required libraries specified in requirements.txt
Usage
1. Clone the repository:
   bash

   git clone https://github.com/imvanshika/Logistic-Regression-Model.git
2. Navigate to the project directory:
   bash
   cd titanic-survival-prediction

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
Run the Jupyter Notebook Code to train the model and make predictions.

## Results
The logistic regression model achieved the following performance metrics on the test dataset:

Accuracy: 0.79
Precision: 0.80
Recall: 0.86
F1-score: 0.83
