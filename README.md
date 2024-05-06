# Alphabet Soup Charity Success Predictor

## Project Overview
This project involves creating a binary classification model that predicts whether applicants will be successful if funded by Alphabet Soup. The dataset provided by Alphabet Soup’s business team consists of thousands of organizations that have received funding over the years.

## Data Preprocessing
The dataset contains several columns capturing various metadata about each organization. The column `IS_SUCCESSFUL` indicates whether the money was used effectively and is the target for our deep learning model. The remaining columns, except for `EIN` and `NAME`, are the features for our model.

## Model Architecture
The deep learning model is composed of multiple hidden layers, each with a varying number of neurons. The `relu` activation function is used for the hidden layers and the `sigmoid` activation function is used for the output layer.

## Results
The model was trained using the training data and then evaluated using the testing data. The model's performance was measured using accuracy. The model achieved an accuracy of around 73%.

## Summary
The deep learning model was able to predict the success of the grant applications with reasonable accuracy. However, there is room for improvement. Future work could involve trying different models, further tuning the model parameters, or applying more feature engineering.
