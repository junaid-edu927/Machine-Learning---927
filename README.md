# 🏠 Home Price Prediction

A beginner-friendly machine learning project focused on predicting house prices using a small dataset and a linear regression model.

## Project Overview
This repository contains a practical machine learning project that demonstrates how to:

- load and inspect a real estate dataset
- clean missing values
- train a regression model
- evaluate prediction accuracy
- use the model to estimate property prices

The project is designed for learning and experimentation, especially for beginners working with Python, Jupyter Notebooks, and scikit-learn.

## Objective
The goal is to predict the price of a house based on features such as:

- `area` — house size in square feet
- `bedrooms` — number of bedrooms
- `house_age` — age of the house in years

The model used in this project is a linear regression model, which is a common and easy-to-understand supervised learning algorithm.

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- scikit-learn

## Repository Contents
- `2.P.02 ML---Project---Home Price Prediction.ipynb` — main notebook for the project workflow
- `2.P.1ML---Project---Home Price Prediction.ipynb` — additional notebook version
- `2.P.3 ML---Project---Home Price Prediction.ipynb` — extended notebook
- `house_price_data.csv` — main dataset used in the project
- `2.P.1 house_price_data.csv` — alternate dataset copy
- `2.P.1 home_price_plots.png` — plot visualizations
- `2.P.02 home_price_prediction_graphs.png` — graph outputs

## Workflow
1. Import the required Python libraries
2. Load the house dataset
3. Explore the dataset and check for missing values
4. Handle missing entries using a suitable strategy
5. Train a Linear Regression model
6. Evaluate the model using metrics like R² score and MAE
7. Predict prices for new input values

## Model Performance
This project reports strong results on the dataset, including:

- `R² Score ≈ 0.97`
- `Mean Absolute Error ≈ ₨18,154`

This indicates that the trained regression model fits the dataset well for educational and demonstration purposes.

## Getting Started

### Prerequisites
Install the required dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
