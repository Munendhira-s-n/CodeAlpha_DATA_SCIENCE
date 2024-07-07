# Titanic Survival Prediction

Predicting survival on the Titanic using machine learning techniques.

## Overview

This project aims to predict the survival of passengers aboard the Titanic using a machine learning model. The dataset includes various features such as passenger class, age, gender, number of siblings/spouses aboard, number of parents/children aboard, fare, and embarkation port.

## Dataset

The Titanic dataset used in this project (`Titanic-Dataset.csv`) contains the following columns:
- `PassengerId`: Unique identifier for each passenger
- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger's name
- `Sex`: Passenger's gender
- `Age`: Passenger's age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Fare paid for the ticket
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure

- **Data Exploration and Preprocessing:** Handling missing values, converting categorical variables to numerical, and feature selection.
- **Model Development:** Building a Random Forest Classifier model using Scikit-learn.
- **Evaluation:** Assessing model performance using accuracy score, classification report, and confusion matrix.
- **Visualization:** Visualizing data distributions, relationships, and model performance metrics.

## Files

- `Titanic-Dataset.csv`: Raw dataset used for analysis and model training.
- `titanic_classification.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, model development, and evaluation.
- `requirements.txt`: List of Python packages required to run the code.

## Usage

To run the Jupyter Notebook and reproduce the analysis:
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
