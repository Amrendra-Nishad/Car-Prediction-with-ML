# Car Price Prediction with Machine Learning

A machine learning regression model that predicts the resale price of used cars based on key vehicle attributes, using Linear Regression.

## Overview

This project builds a model to estimate used car prices from real-world listing data scraped from Quikr, using features like the car's name, company/brand, manufacturing year, kilometers driven, and fuel type.

## Project Goal

To build a machine learning model that accurately predicts the price of a car based on features such as: **name, company, year, kms_driven, and fuel_type**.

## Dataset

- **File:** `quikr_car.csv`
- **Source:** Used car listings scraped from Quikr
- **Features:** Car name, company, year of manufacture, kilometers driven, fuel type
- **Target:** Price (in ₹)

## Approach

1. **Data Cleaning** — Handled messy, real-world scraped data: inconsistent formatting, non-numeric price entries, missing values, and outliers
2. **Exploratory Data Analysis (EDA)** — Analyzed relationships between vehicle attributes (year, kms driven, brand) and price
3. **Feature Engineering** — Encoded categorical variables (company, fuel type) and derived useful features from raw listing data
4. **Model Training** — Trained a **Linear Regression** model to predict car price from the processed features
5. **Evaluation** — Measured model performance using R² score to assess prediction accuracy

## Tech Stack

- **Python**
- **scikit-learn** — model building and evaluation
- **pandas / NumPy** — data cleaning and analysis
- **Matplotlib / Seaborn** — data visualization
- **Jupyter Notebook** — development environment

## How to Run

```bash
# Clone the repository
git clone https://github.com/Amrendra-Nishad/Car-Prediction-with-ML.git
cd Car-Prediction-with-ML

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook "car predicition.ipynb"
```

## Results

The Linear Regression model successfully predicts used car prices based on the key vehicle attributes, capturing the general relationship between a car's age, mileage, brand, and its resale value.

## Future Improvements

- Try more advanced models (Random Forest Regressor, Gradient Boosting) for better accuracy
- Expand the dataset with more recent listings
- Deploy the model as a simple web app where users can input car details and get a price estimate

## Author

**Amrendra Nishad**
[GitHub](https://github.com/Amrendra-Nishad)
