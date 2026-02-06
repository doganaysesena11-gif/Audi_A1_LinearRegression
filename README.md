# Audi A1 Price Prediction (Linear Regression)

## Project Purpose
This project was created while learning Linear Regression.
The goal is to predict Audi A1 car prices based on vehicle features.

## Dataset
Audi A1 listings dataset including:
- Year
- Mileage
- Engine size
- Horsepower (PS)
- Transmission
- Fuel type
- Number of owners

## Data Preprocessing
- Unnecessary columns were removed
- Engine size was converted from string to numeric format
- Categorical variables were encoded using one-hot encoding
- Dataset was split into training and test sets

## Model
- Linear Regression (scikit-learn)
- Model trained on numerical and encoded categorical features

## Evaluation
- R² score is used for evaluation
- Achieved R² score: ~0.91 on the dataset

## Prediction Example
The model can predict car prices for new feature inputs such as year, mileage, engine size, and fuel type.

## Notes
This is a learning-focused project.
Future improvements may include:
- Feature scaling
- Cross-validation
- Testing additional regression models
