# Car-Price-Prediction-Model

This project predicts car prices using a Random Forest Regression model. The dataset is preprocessed using pipelines, encoded using Ordinal & One-Hot encoders, and scaled with StandardScaler. The script also includes an interactive user-input feature for predicting car prices directly from the terminal.

## Features

Loads and preprocesses the CarPrice dataset

Handles numerical and categorical columns

Uses ColumnTransformer + Pipelines

Trains a RandomForestRegressor model

Displays training & testing accuracy

Allows user to enter car details to get price prediction

## How to Run
pip install -r requirements.txt
python your_script_name.py

## Model Outputs

The script prints:

Training Error (MSE)

Training Accuracy (R² Score)

Testing Error (MSE)

Testing Accuracy (R² Score)

Then it asks you to enter car features and returns a predicted price.

## Requirements ---
pandas
numpy
matplotlib
seaborn
scikit-learn
