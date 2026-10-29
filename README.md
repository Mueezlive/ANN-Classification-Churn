## Bank Customer Churn Prediction Using Artificial Neural Networks (ANN)

# Project Overview

This project is an end-to-end deep learning application that predicts whether a bank customer is likely to leave the bank (churn) based on the features given.

Customer churn is a significant challenge in the banking industry, as retaining existing customers is often more cost-effective than acquiring new ones. By leveraging historical customer data and an Artificial Neural Network (ANN), this project aims to identify customers who are more likely to discontinue their relationship with the bank.

The trained model is integrated into an interactive web application built with Streamlit, allowing users to enter customer information and obtain churn predictions.

#Dataset Description

The dataset contains customer information and a target variable indicating whether each customer exited the bank.

Feature Description

CustomerId : Unique identifier assigned to each customer.

Surname : Customer's surname.

CreditScore : Numerical measure of the customer's creditworthiness.

Geography : Country or geographical region associated with the customer.

Gender : Customer's gender.

Age : Customer's age.

Tenure : Number of years the customer has been with the bank.

Balance : Customer's account balance.

NumOfProducts : Number of banking products held by the customer.

HasCrCard : Indicates whether the customer has a credit card.

IsActiveMember : Indicates whether the customer is an active bank member.

EstimatedSalary : Estimated annual salary of the customer.

Exited : Target variable indicating whether the customer left the bank.

Target variable: Exited

#Problem Statement

The project uses a Bank Customer Churn Modelling dataset containing historical customer records, including demographic characteristics, account information, and customer activity.

The objective is to develop a binary classification model that predicts whether a customer will leave the bank.

0 — Not Churned: The customer is expected to remain with the bank.

1 — Churned: The customer is predicted to leave the bank.

This solution demonstrates how deep learning can be applied to customer analytics to support customer retention strategies and data-driven decision-making.

#The Objectives

Perform exploratory data analysis and understand customer behavior.

Preprocess the dataset and prepare features for model training.

Convert categorical variables into numerical representations.

Standardize numerical features where appropriate.

Build and train an Artificial Neural Network using TensorFlow and Keras.

Evaluate the model's performance on unseen data.

Save the trained model and preprocessing objects for reuse.

Develop an interactive Streamlit web application for making predictions.

Deploy the application using Streamlit Community Cloud.
