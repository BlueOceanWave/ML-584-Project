# Code Overview

This repository aims to explore and create models for this car dataset: https://www.kaggle.com/datasets/juanmerinobermejo/us-sales-cars-dataset

We explore variable relationships and train models to predict car prices. 

# File breakdown

`analysis.ipynb`: Explores the dataset and graphs various relationships between variables. Performs some feature engineering on the dataset and creates a new csv file with the updated data   
`modles.ipynb`: Trains and evaluates various models to predict price. Contains Linear Regression, Logistic Regression, XGBoost Decision Tree, and a Feed-forwared Neural Network.   
`cars.csv`: The original dataset from kaggle.com   
`cars-with-features.csv`: An update version of the dataset with additional features generated in `analysis.ipynb`   
