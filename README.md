Titanic Machine Learning Project

A machine learning project based on the Titanic - Machine Learning from Disaster competition. The goal of this project is to predict whether a passenger survived the Titanic disaster using passenger information such as age, gender, ticket class, fare, and family details.

Project Overview

This project includes:

Data preprocessing
Feature engineering
Missing value handling
Categorical encoding
Feature scaling
Machine learning model training
Kaggle submission generation
Dataset

Dataset used from Kaggle Titanic Competition:

train.csv
test.csv

Competition Link:
Titanic Kaggle Competition

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Kaggle Notebook
Feature Engineering

Created new features:

FamilySize
IsAlone
Title

Handled missing values for:

Age
Fare
Embarked
Cabin
Data Preprocessing

Performed:

Label Encoding
Standard Scaling
Feature Selection
Machine Learning Model

Model used:

Random Forest Classifier
Workflow
Load Titanic dataset
Clean and preprocess data
Perform feature engineering
Encode categorical variables
Scale numerical features
Train Random Forest model
Generate predictions
Create submission.csv
Submit predictions on Kaggle
Kaggle Submission

The final submission file contains:

PassengerId,Survived
Results

The model was evaluated using Kaggle leaderboard accuracy_score of 0.7751

Repository Structure
Titanic-ML-Project/
│
├── titanic_model.ipynb
├── submission.csv
├── README.md
Author
Sourav Kumar
