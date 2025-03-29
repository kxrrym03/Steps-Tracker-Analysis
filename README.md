# Steps-Tracker-Analysis
## Steps Tracker - Predicting Calories Burned

## Overview

This project aims to predict the number of calories burned using linear regression based on features such as distance traveled and active minutes. The model is trained using a dataset that tracks step count, distance, active minutes, and calories burned.

## Dataset

## The dataset includes:

Steps: The number of steps taken.

Distance (km): The total distance traveled.

Active Minutes: The duration of active movement.

Calories Burned: The target variable to be predicted.

## Project Structure

Steps Tracker.ipynb - Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

steps_tracker_dataset.csv - The dataset used for training and testing.

## Model & Methodology

Linear Regression

A Linear Regression model was used to predict the calories burned. The model was trained using:

Feature Selection: Distance and Active Minutes

Train-Test Split: 80% training, 20% testing

## Evaluation Metrics:

Mean Squared Error (MSE)

R-squared Score (R²)

## Results

Mean Squared Error (MSE): ~2.42e-30

R² Score: 1.0

Residual plot analysis shows that the model is nearly perfect with minimal residuals.
