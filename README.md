# Multilayer Perceptron (MLP) model

This script demonstrates the training and evaluation of a Multilayer Perceptron (MLP) model on the CIFAR-2 dataset (images of planes and ships). The MLP model is implemented using numpy and consists of linear transform layers, ReLU activation function, and sigmoid cross-entropy loss.

## How does this work?

The script trains an MLP model on the CIFAR-2 dataset using numpy. Here's an overview of how the script works:

1. Data Preparation: The script loads the CIFAR-2 dataset using pickle. It splits the data into training and test sets and stores them in variables.

2. MLP Model: The script defines an MLP model using the provided classes. The model consists of linear transform layers, ReLU activation function, and sigmoid cross-entropy loss. The forward pass and backward pass methods are implemented to compute the model's predictions, gradients, and update the model parameters using gradient descent with momentum and L2 regularization.

3. Training: The script iterates over the specified number of epochs and mini-batches. For each mini-batch, it selects a batch of examples and labels, performs forward and backward passes, and updates the model's parameters. The loss and accuracy are computed during training and printed after each epoch.

4. Evaluation: After training, the script evaluates the trained model on the training and test sets. It computes the loss and accuracy using the forward pass and evaluates the predicted labels against the true labels.

## Usage

To use this script, follow these steps:

1. Clone the repository and navigate to the project directory:
   ```shell
   git clone https://github.com/Sid1279/MLP-CIFAR2-scratch-model.git
   cd MLP-CIFAR2-scratch-model
   ```

