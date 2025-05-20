# Stock_Prediction

A simple machine learning project for predicting stock prices using the K-Nearest Neighbors (KNN) regression algorithm.

## Overview

This project demonstrates how to use the KNN algorithm to predict future stock prices based on historical data. The code covers data preprocessing, model training, prediction, and visualization using Python.

## Features

- Loads and preprocesses historical stock price data
- Implements KNN regression for stock price prediction
- Evaluates model performance using Mean Squared Error (MSE)
- Visualizes actual vs. predicted stock prices

## Installation

1. **Clone the repository:**
    ```
    git clone https://github.com/garg0711/Stock_Prediction.git
    cd Stock_Prediction
    ```

2. **Install required packages:**  
    ```
    pip install numpy pandas scikit-learn matplotlib quandl
    ```

## Usage

1. **Prepare your data:**  
    Place your stock data CSV file (with columns like `Date` and `Close`) in the project directory.

2. **Run the code:**  
    Open and run the Python script or Jupyter Notebook provided in the repository.  
    Make sure to update the filename in the code to match your CSV file.

3. **View results:**  
    The script will output the Mean Squared Error and display a plot comparing actual and predicted stock prices.

## Project Structure

