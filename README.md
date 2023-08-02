# AQI-Prediction-Model

## Overview

This project aims to predict the Air Quality Index (AQI) of the surrounding environment using machine learning techniques. The AQI is an important environmental indicator that provides valuable information about air pollution levels and its potential impacts on health and the environment.

## Dataset

The dataset used for training and testing the ML models was created through the following steps:

- Climate data was collected from the internet using the retrieve_html.py script.
- The collected data was processed and combined using the plot_AQI.py script, resulting in the Real_Combine.csv file, which serves as the final dataset.

## Requirements

- Python (>= 3.6)
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## Installation

1. Clone the repository to your local machine:

```bash

git clone https://github.com/MadhavJain0119/AQI-Prediction-Project.git
cd AQI-Prediction-Project
``` 

2. Install the required dependencies:

```pip install -r requirements.txt```

## Usage

- Ensure you have installed all the dependencies.
- Run the retrieve_html.py script to collect climate data from the internet.
- Use the plot_AQI.py script to combine and process the collected data, resulting in Real_Combine.csv.
- Open the Jupyter Notebooks to explore different ML algorithms and evaluate their performance.

## Model Evaluation

Multiple ML algorithms, including Linear Regression, Decision Tree Regressor, Lasso Regression, XGBoost, Gradient Boost, and AdaBoost, have been tested and evaluated for their performance. The best-performing model has been identified using the Root Mean Squared Error (RMSE) metric.

## Final Model

The Voting Regressor has been selected as the final model for AQI prediction. This ensemble model combines the predictions of several base models, providing improved accuracy and robustness.
