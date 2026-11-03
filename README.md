# Car Price Prediction

A beginner Machine Learning project that predicts the selling price of used cars based on their features.

## Project Overview

The goal of this project is to understand the end-to-end Machine Learning workflow by building a regression model to estimate used car prices.

## Dataset

The project uses the **Car Details from Car Dekho** dataset.

Features include:

* Car name
* Manufacturing year
* Kilometres driven
* Fuel type
* Seller type
* Transmission
* Previous owner

**Target variable:** `selling_price`

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Gradio
* Pickle

## Project Workflow

1. Load and inspect the dataset
2. Clean the data and remove duplicates
3. Perform exploratory data analysis (EDA)
4. Identify and handle outliers
5. Encode categorical features
6. Split the data into training and testing sets
7. Train regression models
8. Evaluate and compare model performance
9. Predict the price of a new car
10. Create a simple Gradio interface

## Machine Learning Models

The following regression models were explored:

* Linear Regression
* K-Nearest Neighbors (KNN) Regressor
* Decision Tree Regressor

## Model Evaluation

Models were evaluated using:

* **RMSE:** Measures the size of prediction errors. Lower is better.

Based on the RMSE values from my experiments, the Decision Tree Regressor performed best among the three models tested.

## How to Run

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd <your-repository-folder>
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn gradio
   ```

4. Open the Jupyter Notebook and run the cells in order.

## Project Learning

Through this project, I practiced:

* Data preprocessing and feature encoding
* Exploratory data analysis
* Regression model training and evaluation
* Making predictions on new data
* Building a basic ML interface

## Limitations

* The model's predictions are estimates and may not reflect actual market prices.
* The dataset may not represent current prices across all locations.
* Label encoding car names may introduce an artificial numerical relationship between categories.
* Model performance can be improved through further feature engineering and experimentation.

## Author

**Bhavani Bollepelli**
