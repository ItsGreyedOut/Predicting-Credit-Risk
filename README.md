## PENDING, in progress!

# Supervised Machine Learning Project - Predicting Credit Risk

In this project, I will be building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

I used the data to create machine learning models to classify the risk level of given loans. Specifically, I compared the Logistic Regression model and Random Forest Classifier.

## Preprocessing: Convert categorical data to numeric

First I created a training set from the 2019 loans using `pd.get_dummies()` to convert the categorical data to numeric columns. Similarly, I also created a testing set from the 2020 loans, also using `pd.get_dummies()`. 

## Consider the models

I created and compared two models on this data: a logistic regression, and a random forests classifier. Before I created, fit, and score the models, I made a prediction as to which model I thought would perform better. 

## Fit a LogisticRegression model and RandomForestClassifier model

I created a LogisticRegression model, fit it to the data, and printed the model's score. Then I did the same for a RandomForestClassifier. I randomly chose a hyperparameters and compared my predection to the results.

## Revisit the Preprocessing: Scale the data

The data going into these models was never scaled therefore I used `StandardScaler` to scale the training and testing sets. Before re-fitting the LogisticRegression and RandomForestClassifier models on the scaled data, I made another prediction about how I thought scaling would affect the accuracy of the models.

