# Red Wine Quality Prediction

## Overview
This project aims to determine the quality of red wine using Machine Learning techniques. The quality of the wine is predicted using two different approaches:
1. Direct prediction of the label-encoded quality.
2. Classification of wine into 'good' and 'bad' categories based on a benchmark.

## Data
The project uses a CSV file containing various chemical properties of red wine and their corresponding quality ratings. The dataset includes features such as acidity, sugar levels, pH, and alcohol content.

## Model
The project uses two models:
1. **K-Nearest Neighbors (KNN)**: Used to predict the label-encoded quality of the wine.
2. **Support Vector Machine (SVM)**: Applied to classify the wine into 'good' and 'bad' categories.

## Usage
- **Data Preparation**: Ensure the CSV file containing the wine data is in the correct format.
- **Data Analysis**: Perform Exploratory Data Analysis (EDA) to understand the dataset and uncover patterns.
- **Data Preprocessing**: Clean and preprocess the data, including handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**:
  - **KNN**: Run the provided Jupyter notebook or Python script to train the KNN model on the data.
  - **SVM**: Run the provided Jupyter notebook or Python script to train the SVM model on the data.
- **Prediction**: Use the trained models to predict the quality and classify the wine.
- **Model Saving**: Save the trained models using pickle for future use.

## Results
The project aims to achieve accurate predictions of wine quality and effective classification of wines into 'good' and 'bad' categories. The results will be evaluated using metrics like accuracy, confusion matrix, precision, recall, and F1-score.

## Contributor
Unnati Agarwal
