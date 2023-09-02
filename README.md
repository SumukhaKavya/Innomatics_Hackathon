# Taxi Ride Data Analysis and Prediction

## Project Description

This project involves the analysis and prediction of taxi ride data recorded between January 1, 2009, and June 30, 2015. The dataset consists of various attributes, including ride details, date and time information, and fare amounts. The goal of this project is to gain insights from the data, perform machine learning modeling to predict fare amounts, and evaluate model performance.

## Key Findings

- **Dataset Shape**: The dataset contains [200000] rows and [8] columns.

- **Missing Values**:
  - The 'dropoff_longitude' column has [1] missing values.
  - The 'dropoff_latitude' column has [1] missing values.

- **Data Types**: The 'pickup_datetime' feature is of data type [object] and is converted into [datetime].

- **Data Cleaning**: Null values were removed from the dataset using the [dropna()] function.

## Further Analysis in Jupyter Notebook

After the data cleaning process, in-depth analysis and additional insights were explored in a Jupyter Notebook. The code and detailed analysis are available in the Jupyter Notebook files provided in this repository.

- **Machine Learning Models**:
  - Linear Regression Model:
    - Adjusted R-squared ≈ 0.0006

  - Random Forest Regression Model:
    - Adjusted R-squared ≈ 0.660

## Usage

To explore the analysis and machine learning models in this project:

1. Clone the repository to your local machine.
2. Install the necessary dependencies as mentioned in the project.
3. Refer to the analysis code and machine learning models for insights and predictions.
