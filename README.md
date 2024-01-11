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

Three notebooks are included in this repository. The first two notebooks have their own repo, but I also put them here to complete the collection.
1. tps_apr2022_rocket focus on ROCKET as a feature extractor. The video is [here](https://youtu.be/0c0YNWo9Xyg)
2. shapelet_tslearn focus on Shapelets to transform the dataset. The video is [here](https://youtu.be/u69v5gm_zBk). Note that I didn't set the seed for learning shapelets, so the shapelets visualizations in this notebook may look a little bit different than what you see in the video. But that doesn't affect the model performance.
3. The video for models with low AUC is [here](https://youtu.be/LCIpAKJKrQ8). In that video I also share my opinion about what we can learn from this project.
