# House Price Prediction

This project utilizes Flask for deployment and employs Linear Regression for modeling house prices. While GridSearchCV was experimented with for hyperparameter tuning, the initial Linear Regression model yielded the best results.

## Overview

This project aims to predict house prices based on various features such as square footage, number of bedrooms, bathrooms, location, etc. By leveraging machine learning techniques, specifically Linear Regression, we've developed a model capable of estimating house prices with reasonable accuracy.

## Dataset

The dataset used for this project is the Bengaluru House Price Data available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data). This dataset provides information about various features of houses in Bengaluru, including location, size, number of bedrooms, bathrooms, and price.

## Deployment

The application is deployed using Flask, a lightweight WSGI web application framework in Python. With Flask, we've created a user-friendly interface where users can input relevant features of a house and receive a predicted price based on the trained model.

## Model Development

### Linear Regression

Linear Regression was chosen as the primary modeling technique due to its simplicity and interpretability. By fitting a linear relationship between the input features and the target variable (house prices), we've created a predictive model that provides a baseline for house price estimation.

### GridSearchCV

GridSearchCV, a method for hyperparameter tuning in machine learning models, was also employed to optimize the performance of the Linear Regression model. However, after experimentation, it was found that the default hyperparameters provided satisfactory results, and the initial model performed the best.

## Usage

To use the House Price Prediction application:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies (if not already installed).
4. Run the Flask application (`server.py`).
5. Access the application through your web browser.

## Dependencies

Ensure the following dependencies are installed:

- Flask
- scikit-learn
- pandas
- numpy

You can install these dependencies using pip.

## Screenshots

<img width="959" alt="h1" src="https://github.com/binisha-banjara/House-Price-Prediction/assets/107851119/b102c537-3b42-4056-b9ba-27dd9b1550d4">



<img width="956" alt="h3" src="https://github.com/binisha-banjara/House-Price-Prediction/assets/107851119/0220c753-71ce-4228-8910-45ffa7747cd7">



<img width="959" alt="h4" src="https://github.com/binisha-banjara/House-Price-Prediction/assets/107851119/200e95c7-cdcb-42bb-b970-4b252dde9cbc">



