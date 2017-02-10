# bike-rental-neural-network

In this project, I built a neural network only using numpy as a dependency and used it to predict daily bike rental ridership.

## Architecture

The neural network has 2 layers 

  - 1 hidden layer with 30 nuerons
  - Output layer with 1 neuron
  - input layer has 56 neurons, 1 for each feature of the bike rental data to train from.

### Hyperparameters

  - epochs: 3000
  - learning rate: 0.01
  - Mini batch SGD size: 128

## Results

  - Training loss: 0.061 
  - Validation loss: 0.130
