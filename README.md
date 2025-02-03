# Lung Capacity Prediction using Linear Regression

Overview

This project applies Linear Regression to predict lung capacity based on various physiological factors. The model is trained on a dataset containing lung capacity measurements and related features such as age, height, and smoking habits.

Dataset

The dataset includes:

Age (years)

Height (cm)

Smoking Habit (Yes/No)

Lung Capacity (Liters - Target Variable)

Gender 

Objective

The main goal is to build a predictive model that estimates lung capacity given certain physiological parameters. This can be useful in medical research and preliminary health assessments.

Technologies Used

Python

Pandas & NumPy (Data Manipulation)

Matplotlib & Seaborn (Data Visualization)

Scikit-learn (Machine Learning)

Installation

To run this project, install the required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

Implementation Steps

Data Preprocessing: Cleaning missing values and encoding categorical data.

Exploratory Data Analysis (EDA): Visualizing feature distributions and correlations.

Feature Engineering: Normalization and feature selection.

Model Training: Applying Linear Regression and evaluating performance.

Evaluation: Using metrics like Mean Squared Error (MSE) and R-squared.

Usage

Run the script lung_capacity_regression.py:

python lung_capacity_regression.py

This will train the model and display evaluation metrics along with visualizations.

Results

R-squared Score: Measures the model's goodness of fit.

MSE: Assesses prediction error.

Future Improvements

Incorporate more features like weight and exercise habits.

Experiment with advanced regression models like Polynomial Regression.

Implement a web-based interface for user interaction.

Contributing

Feel free to fork this repository and submit pull requests for enhancements!
