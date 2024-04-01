# Apple-quality-prediction
Neural network for predicting whether an apple quality is good or bad based on some attributes of it. 

Trained on dataset from kaggle 

## Dataset
https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality

## Metrics
After training for 20_000 epochs I achieved around 93% accuracy on test data. Probably the training could be stopped earlier with no accuracy drop, however because I didn't experience overfitting with this setup I decided to leave it like that. 

For neural network architecture I chose three hidden layers with sizes [40, 50, 30] and sigmoid as an activation function on every step. 

To avoid overfitting dropout is applied on every layer with p=0.3
