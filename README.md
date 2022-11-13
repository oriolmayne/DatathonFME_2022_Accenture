# Datathon FME 2022 - Accenture Challenge

## Introduction

This repository contains the code for the Accenture Challenge of the Datathon FME 2022. The challenge consists of analyzing the data of the [Kaggle competition](https://www.kaggle.com/competitions/datathon-2022-upc-accenture/overview) to extract insights about the factors that influence if a product will be delivered on time or not.

Aditionally, we have to create a model that predicts if a product will be delivered on time or not based on the data provided.

## Project structure

The project is structured as follows:

- `Datasets`: contains the data used for the challenge, both the original data and the data after the preprocessing.
- `Predictions`: contains the predictions of the models created.
- `DLmodel`: contains the trained model of the deep learning model.
- `DataVisualization.ipynb`: notebook used to visualize the data.
- `DecisionTreeClassifier.ipynb`: notebook used to train the decision tree classifier model.
- `LogRes+DL.ipynb`: notebook used to train both the logistic regression model and the deep learning model.

## Results

The best model obtained was the logistic regression model with a ROC AUC score of 0.81. This is the model used to make the final predictions.

The deep learning model obtained a ROC AUC score of 0.64, wich is way lower than the logistic regression model. This model is not used to make the final predictions.

The decision tree classifier model obtained a ROC AUC score of 0.76, wich is also lower than the logistic regression model. Nonetheless, this model has a great interpretability, so it can be used to extract insights about the data. 
## Team
* Jonathan Rodríguez Barja
* Thomas González Saito
* Oriol Mayné comas
