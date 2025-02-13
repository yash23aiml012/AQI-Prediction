# AQI-Prediction
Air Quality Index (AQI) Prediction

Overview

This project aims to predict the Air Quality Index (AQI) using data from the UCI Air Quality dataset. The dataset contains air pollution measurements and meteorological data collected from an urban environment. The notebook provides data preprocessing, exploratory data analysis (EDA), and modeling steps.

Dataset

The dataset is loaded from AirQualityUCI.csv.
Values are separated by ; instead of commas.
Some numerical values use , as a decimal separator and need conversion.
Missing values are encoded as -200 and require handling.
Only the first 9357 rows are valid; the rest contain null values.
Requirements

To run this notebook, install the following dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn
Steps Covered

Data Loading
Reads the CSV file into a Pandas DataFrame.
Handles separators and missing values.
Data Preprocessing
Identifies and replaces missing values.
Converts necessary columns into numerical format.
Exploratory Data Analysis (EDA)
Visualizes distributions of pollutants.
Identifies correlations between features.
Modeling
Implements regression or classification models for AQI prediction.
Evaluates model performance.
Usage

Open the Jupyter Notebook and run the cells step by step.
Modify preprocessing steps if needed to fit other datasets.
Train and evaluate different models for AQI prediction.
Data Source

The dataset is sourced from the UCI Machine Learning Repository.
