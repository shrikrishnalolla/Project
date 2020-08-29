The project attempts to classify SDSS telescope data into Galaxy,Star or Quasar.This is done by implementing an Artificial Neural Network(ANN) from scratch.

The dataset is taken from Sloan Digital Sky Survey DR14 dataset on Kaggle.The link is given below : 

https://www.kaggle.com/lucidlenn/sloan-digital-sky-survey

The Artificial Neural Network(ANN) has 1 input layer,2 hidden layer and 1 softmax output layer. The hidden layers have 128 and 64 neurons respectively. The model runs gradient descent with L2 regularization and retruns a train and test accuracy of approximately 97%. 
