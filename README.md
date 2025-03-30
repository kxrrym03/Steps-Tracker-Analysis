# Steps-Tracker-Analysis
## Steps Tracker - Predicting Calories Burned

## Overview

This project aims to predict the number of calories burned using linear regression based on features such as distance traveled and active minutes. The model is trained using a dataset that tracks step count, distance, active minutes, and calories burned. It also implements a Support Vector Machine (SVM) model to predict mood based on fitness tracking data. The model analyzes various health metrics like steps, distance, calories burned, active minutes, sleep hours, and water intake to classify the user's mood into categories like "energetic", "happy", "sad", "stressed", or "tired".

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

# Linear Regression

A Linear Regression model was used to predict the calories burned. The model was trained using:

Feature Selection: Distance and Active Minutes

Train-Test Split: 80% training, 20% testing

#Support Vector Machine

Converted mood categories to numerical values using LabelEncoder:

energetic: 0

happy: 1

sad: 2

stressed: 3

tired: 4

Scaled features using StandardScaler for better model performance

Used scikit-learn's SVC (Support Vector Classification) with a linear kernel

Split data into 80% training and 20% testing sets

Achieved 100% accuracy on the test set (note: this may indicate overfitting)

## Evaluation Metrics:

Mean Squared Error (MSE)

R-squared Score (R²)

## Results

Mean Squared Error (MSE): ~2.42e-30

R² Score: 1.0

Residual plot analysis shows that the model is nearly perfect with minimal residuals.
Accuracy: 1.0

Precision: 1.0 for all classes

Recall: 1.0 for all classes

## Dependencies
Python 3.x

pandas

numpy

scikit-learn

matplotlib

seaborn

Author
Kerry

License
This project is open source and available under the MIT License.
