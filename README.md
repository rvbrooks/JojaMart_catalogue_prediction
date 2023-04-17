# JojaMart_catalogue_prediction
I build a supervised machine learning model data pipeline for predicting which products JojaMart will discontinue next catalogue update.

## JojaMart's problem statement:
JojaMart regularly updates its product catalogue in their Stardew branch. 
To improve the efficiency of inventory management when they update their catalogue, they would like a model to predict which items will be discontinued the next time the catalogue is updated (which occurs every 6 months).

## Solution Summary
1. After performing EDA and data cleaning, I test a simple logistic regression (LR) model on the data. 
2. Finding poor performance in the LR model, I try a Random Forest model.
3. Finding good performance, I perform hyperparameter tuning of the model and build a data pipeline.

## Project Contents

- 1_JojaMart_EDA.ipynb : a notebook containing exploratory data analysis (EDA) of JojaMart's data.
- 2_JojaMart_model_training.ipynb : a notebook where supervised machine learning models (e.g. Random Forest classifier) are trained on JojaMart's data.
- datasheet_1.csv : comma-separated data provided by JojaMart.
- datasheet_2.csv : more comma-separated data provided by JojaMart.
