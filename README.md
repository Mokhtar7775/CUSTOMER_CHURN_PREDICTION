
# Customer Churn Prediction Project

## Overview

This repository contains the code and resources for a customer churn prediction project. The goal of this project is to build a machine learning model that predicts whether a customer is likely to churn from a subscription-based service or business.

## Dataset

The project uses a dataset with the following columns:

- `RowNumber`: Row number in the dataset
- `CustomerId`: Unique identifier for each customer
- `Surname`: Customer's surname
- `CreditScore`: Customer's credit score
- `Geography`: Customer's geographical location
- `Gender`: Customer's gender
- `Age`: Customer's age
- `Tenure`: Number of years the customer has been with the service
- `Balance`: Customer's account balance
- `NumOfProducts`: Number of products the customer has subscribed to
- `HasCrCard`: Whether the customer has a credit card (1 for Yes, 0 for No)
- `IsActiveMember`: Whether the customer is an active member (1 for Yes, 0 for No)
- `EstimatedSalary`: Estimated salary of the customer
- `Exited`: Target variable indicating whether the customer has churned (1 for Yes, 0 for No)

## Model Building

The project uses machine learning algorithms such as Logistic Regression, Random Forests, and Gradient Boosting to predict customer churn. The models are trained and evaluated on historical customer data, considering features like usage behavior, demographics, and financial information.

## Results

- Gradient Boosting Accuracy: 86%
