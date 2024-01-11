# time-series-classification-on-sensor-data

## Data
The data is from a Kaggle competition Tabular Playground Series April 2022. The multivariate time series consists of 13 time series, each of which has 60 data points.

## Goal
This is a binary classification problem, so we need to predict the probability of an input being in group 1. 

## Models
I tried various approaches, both in the feature extraction and in the modelling stages. <br>
- Feature extraction
  * ROCKET
  * Shapelets
  * None
- Modelling
  * Gradient Boosting
  * Neural Network (the basic, a fully connected layer)
  * LSTM
  * Logistic regression

Three notebooks are included in this repository.

The video for models with low AUC is [here](https://youtu.be/LCIpAKJKrQ8). In that video I also share my opinion about what we can learn from this project.
