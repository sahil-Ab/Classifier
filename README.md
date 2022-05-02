# Multi-label Classifier using Keras API
This project is a sample for creating a basic multilabel ensemble classifier. It creates 'n' - number of fully connected neural network and predicts result from an ensemble of those models. The focus of the
project is only on creating a ensemble network and not on accurate model. The projects expects clean input data. 

** This readme.md was created after the submission. 

## Prerequisites

The projects needs the following libraries - 
* Tensorflow
* Numpy
* Pands
* Matplotlib

## Running the code
The script expects two files - 
> train.csv 
> test.csv

The training/test data should have the target variable names - 'Y'. 

## Possible improvements 
The code in this case is run for very few epochs to show the proof of concept and not generate actual outputs. Model's parameter could be controlled for better results. 
Some of the paramters like epochs/learning rate are unrealistic and not expected to produce results. 
The following suggestions are some of the methods to improve the models - 
- Exception handling
- Change slicing of train/test dataset from column name to last column 
- Adding assertions
- Creating separate functions to compile and fit models
- Creating separate function for plotting charts
- Accuracy measure of each network should be plotted on the same plot
- Controlling output neurons
- Adding possibility to manage optimizers/losses/metrics
- Input should decide the set of neurons for each neural network
- Paramters like no of neurons, epochs, learning rate, activation function, etc should be managed from the calling statment
- Prediction is specific to the used test data, variable `res` should be managed from input data
- Model should be evaluated on a range of metrics to find actual performance, rather than just accuracy
- Output could simply output only one precition instead of probabilities of all possible classes, etc. 
- Output probabilities could be rounded for better readability
- Regularization techniques lile L1/L2 or dropout could be used 

Suggestions are welcome for further improvement of the project. 
