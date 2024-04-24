# Car Price Prediction Model

## Overview
This repository contains code for building a machine learning model to predict car prices based on the Car Dataset from Kaggle. The dataset comprises information about various cars including their make, model, price, year, mileage, fuel type, transmission, and more.

## Dataset Source
The dataset used in this project can be found on Kaggle: [kaggle.com](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=Car+details+v3.csv)

## Features
- **Make:** Manufacturer or brand of the car.
- **Model:** Model name or number of the car.
- **Price:** Price of the car in the local currency.
- **Year:** Manufacturing year of the car.
- **Kilometer:** Mileage or distance traveled by the car in kilometers.
- **Fuel Type:** Type of fuel used by the car (e.g., Diesel, Petrol, CNG).
- **Transmission:** Type of transmission (e.g., Manual, Automatic).
- **Location:** Location where the car is available or registered.
- **Color:** Exterior color of the car.
- **Owner:** Ownership type (e.g., First owner, Second owner).
- **Seller Type:** Type of seller (e.g., Individual, Corporate).
- **Engine:** Engine displacement in cubic centimeters (cc).
- **Max Power:** Maximum power output of the engine in brake horsepower (bhp) at a specific RPM.
- **Max Torque:** Maximum torque produced by the engine in Newton-meters (Nm) at a specific RPM.
- **Length, Width, Height:** Dimensions of the car.
- **Seating Capacity:** Number of seats in the car.
- **Fuel Tank Capacity:** Capacity of the fuel tank in liters.

## Steps Involved
1. **Data Preprocessing:** Cleaning data, handling missing values, and feature engineering.
2. **Exploratory Data Analysis (EDA):** Understanding relationships and patterns in the data through visualizations.
3. **Modeling:** Building a machine learning pipeline using Linear Regression for price prediction.
4. **Evaluation:** Assessing model performance using metrics like Mean Squared Error (MSE) and R-squared (R2) scores.

## Files in Repository
- **car_price_prediction.ipynb:** Jupyter Notebook containing code for data preprocessing, modeling, and evaluation.
- **car_details.csv:** Dataset used in the project.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the `car_price_prediction.ipynb` notebook in Jupyter environment.
4. Follow the code and comments to understand each step of the project.

## Contribution
Contributions are welcome! Here are a few ways you can contribute:
- Improve data preprocessing techniques.
- Experiment with different machine learning algorithms for modeling.
- Enhance visualization and insights in EDA.
- Update the README with additional information or corrections.

## License
This project is licensed under the [MIT License](LICENSE).

