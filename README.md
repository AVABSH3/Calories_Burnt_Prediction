# Calories Burnt Prediction System

This project is designed to predict calories burnt during physical activities based on various features such as user details, duration of exercise, heart rate, and body temperature. The XGBRegressor algorithm is employed for its predictive capabilities. The dataset used contains information on user demographics and exercise-related metrics.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

The Calories Burnt Prediction System aims to forecast the number of calories burned during physical activities. It leverages the XGBRegressor algorithm, known for its ability to handle complex relationships in the data and provide accurate predictions.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/calories-burnt-prediction.git
   cd calories-burnt-prediction
Install Dependencies:

bash
pip install -r requirements.txt
Run the Application:

bash
python calories_burnt_prediction.py

## Usage
Load the dataset containing user details and exercise metrics.
Preprocess the data, including handling missing values and encoding categorical features.
Split the data into training and testing sets.
Train the XGBRegressor model on the training set.
Evaluate the model's performance using metrics such as Mean Squared Error.
Make predictions on calories burnt using the trained model.

## Features
Predict calories burnt using the XGBRegressor algorithm.
Evaluate model performance with scikit-learn metrics.
Utilize user demographics and exercise-related metrics for accurate predictions.

## Dependencies
NumPy
Pandas
XGBoost
Scikit-learn
Matplotlib
Seaborn

## Acknowledgements
The dataset used in this project is credited to Kaggle.
XGBRegressor is implemented using the XGBoost library.

## License
This project is licensed under the MIT License.
