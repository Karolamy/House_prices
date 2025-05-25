# House Price Prediction

This project focuses on predicting house prices using a cleaned dataset and machine learning models. 
The dataset is preprocessed by handling missing values, encoding categorical features, and separating training and test data.

## Project Overview

- Data cleaning and preprocessing
- Encoding categorical features
- Handling missing values with mean and mode strategies
- Visualizing predicted vs. actual sale prices
- Training three models:
  - Linear Regression
  - Random Forest Regressor
  - Polynomial Regression
- Comparing model performance using Mean Squared Error
- Generating a final prediction file (`rf_output.csv`) using the Random Forest model

## Files

- `rf_output.csv`: Final predictions on test data
- `exploring.ipynb`: Contains all preprocessing, training, and visualization code

## Models Used

- **Linear Regression**: Basic regression model for baseline comparison
- **Random Forest Regressor**: Performed best on test data
- **Polynomial Regression**: Captures non-linear relationships

## Results

The Random Forest model gave the lowest error and was chosen for final predictions.
