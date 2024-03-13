# 🖧 Multilayer Perceptron (MLP) neural network model 

This script demonstrates the training and evaluation of a Multilayer Perceptron (MLP) model on the CIFAR-2 dataset (images of planes and ships). The MLP model is implemented using numpy and consists of linear transform layers, ReLU activation function, and sigmoid cross-entropy loss.

## 🌐 MLP Model Architecture
The model consists of linear transform layers, a ReLU activation function, and sigmoid cross-entropy loss. The forward pass and backward pass methods are implemented to compute the model's predictions, gradients, and update the model parameters using gradient descent with momentum and L2 regularization.

## 🔍 Training
The script iterates over the specified number of epochs and mini-batches. For each mini-batch, it selects a batch of examples and labels, performs forward and backward passes, and updates the model's parameters. The loss and accuracy are computed during training and printed after each epoch.

After training, the script evaluates the trained model on the training and test sets. It computes the loss and accuracy using the forward pass and evaluates the predicted labels against the true labels.
