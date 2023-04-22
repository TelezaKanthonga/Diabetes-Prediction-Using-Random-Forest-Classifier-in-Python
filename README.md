# Diabetes-Prediction-Using-Random-Forest-Classifier-in-Python
This repository contains code for predicting diabetes using machine learning techniques. It demonstrates how to load and preprocess data, 
train a Random Forest Classifier, and evaluate the model's accuracy.

## Requirements
- pandas
- numpy
- scikit-learn

## Dataset

The dataset used for training and testing the model is the Pima Indians Diabetes dataset, which can be found at
(https://www.kaggle.com/uciml/pima-indians-diabetes-database).

## Notes

- This model replaces zero values in certain columns with the mean value of the respective column.
- The data is split into training and testing sets with a test size of 0.2 and a random state of 0.
- The random forest classifier is trained with 100 estimators and a random state of 0.

## Usage

You can run the code on Google Colaboratory or Jupyter Notebook after installing the required packages.
After running the code, you will see the accuracy score of the trained model on the test dataset. 
The current implementation of the notebook achieved an accuracy of 0.90.

## Acknowledgements

The Pima Indians Diabetes dataset was obtained from the Kaggle, (https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
