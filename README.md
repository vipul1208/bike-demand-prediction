# Bike Demand Prediction using Multiple Linear Regression

## Project Description

This project involves building a multiple linear regression model to predict the demand for shared bikes. The dataset used for this project is provided by BoomBikes, a bike-sharing service. The goal is to understand the factors affecting bike demand and to build a model that can predict future bike rentals.

### Problem Statement

BoomBikes has experienced a decline in revenues due to the ongoing pandemic and is looking to prepare for an increase in bike demand once the situation improves. To achieve this, the company needs to identify key factors influencing bike demand and build a predictive model.

### Dataset

The dataset contains daily records of bike rentals with various independent variables. Some of the key variables include temperature, humidity, windspeed, and weather conditions. The target variable for this prediction is the total number of bike rentals (`cnt`), which is the sum of casual and registered users.

## Installation

### Prerequisites

- Python 3.6 or higher
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

You can install the required libraries using pip:

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

Cloning the Repository
Clone this repository to your local machine using:

git clone https://github.com/vipul1208/bike-demand-prediction.git

## Usage

1. **Load the Dataset**: The dataset is loaded using `pandas`. Ensure that the dataset file (`day.csv`) is in the same directory as the Jupyter notebook.

2. **Data Preparation**:
    - Convert categorical variables into string values.
    - Drop unnecessary columns.
    - Perform feature scaling using `MinMaxScaler`.

3. **Model Building**:
    - Split the dataset into training and testing sets.
    - Build a multiple linear regression model using `statsmodels` and `scikit-learn`.
    - Perform feature selection and evaluate the model using R-squared and Adjusted R-squared scores.

4. **Model Evaluation**:
    - Predict bike demand on the test set.
    - Calculate R-squared score using `sklearn.metrics`.

5. **Visualization**:
    - Generate plots to visualize the relationship between features and the target variable.
    - Plot error terms and predictions.

To run the analysis, open the Jupyter notebook (`bike_demand_prediction.ipynb`) and follow the instructions within the notebook.

## Example

To run the analysis, execute the Jupyter notebook:

```bash
jupyter notebook bike_demand_prediction.ipynb
