# Handwritten Digit Recognition

## Dataset Description
* Dataset used : MNIST from tensorflow examples
* The dataset consists of 55000 train and 10000 test images of size 28 X 28 of handwritten digits from 0 to 9

## Approach
* Imported the dataset
* Implemented a Neural Network using tensorflow having 2 hidden layers with 256 units each and 1 output layer having 10 unit. Optimizer used : Adam Optimizer. Loss function : Softmax Cross Entropy
* Executed the NN
* Implemented a CNN using tensorflow having 2 convolution layers, 2 pooling layers, 1 hidden layer and 1 output layer. Optimizer used : Adam Optimizer. Loss function : Softmax Cross Entropy
* Executed the CNN

## Results
* Accuracy using NN : 97.02%
* Accuracy using CNN : 98.49%

## Further Scope
The experimentation with number of layers, optimizers, loss function and number of iteration can be done to achieve better accuracy.
