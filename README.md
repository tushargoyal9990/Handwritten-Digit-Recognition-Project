# Handwritten Digit Recognition

## Introduction
The project aims to classify the MNIST dataset images using Neural Network (NN) and Convolutional Neural Network (CNN). 

## Dataset Description
MNIST (Modified National Institute of Standards and Technology) dataset is available in tensoflow examples. The dataset consists of 55000 train and 10000 test images of size 28 X 28 of handwritten digits divided in 10 classes from 0 to 9. 

![alt text](https://github.com/tushargoyal9990/Handwritten-Digit-Recognition-Project/blob/main/Images/MNIST%20Dataset.png)


## Neural Network
Neural Network, as the name suggests, is a network based on the biological neurons first proposed in 1943 by Warren McCullouch and Walter Pitts. It is fundamentally a densely connected network of small processing units called nodes. Each nodes can take multiple inputs, add them together and perform the specified function to give an output that can futher feed into many nodes. The architecture of NN for MNIST dataset is as follow: 

![alt text](https://github.com/tushargoyal9990/Handwritten-Digit-Recognition-Project/blob/main/Images/NN%20Architecture.PNG)

The model is trained for 30 iterations with a batch size of 50 using Adam Optimizer having a learning rate of 0.001.

## Convolutional Neural Network
Convolutional Neural Networks CNNs are one of the most effective deep learning techniques used for image recognition and classification. The core of a CNN is to perform convolution operation to learn features of the input images. A CNN may consist of convolutional layer, activation layer,  pooling layer, dropout layer, and fully-connected dense layer. A loss function is used to calculate loss between output of the network and the ground truth which is then minimized using optimizer by doing back propagation for a number of times, called epochs. Initialization of weights, learning rate of optimizer, number of epochs, loss function, dropout rate, activation function, kernel size, number of filters, etc. are some hyperparameters that can be adjusted to achieve better results. The architecture of CNN for MNIST dataset is as follow: 

![alt text](https://github.com/tushargoyal9990/Handwritten-Digit-Recognition-Project/blob/main/Images/CNN%20Architecture.PNG)

The model is trained for 100 iterations with a batch size of 100 using Adam Optimizer having a learning rate of 0.01.

## Results

Classification Report of NN:

![alt text](https://github.com/tushargoyal9990/Handwritten-Digit-Recognition-Project/blob/main/Images/NN%20Report.PNG)

Classification Report of CNN:

![alt text](https://github.com/tushargoyal9990/Handwritten-Digit-Recognition-Project/blob/main/Images/CNN%20Report.PNG)

## Conclusion
CNN has better performance than NN because it is specifically designed for computer vision related tasks (though CNNs can be used in many different types of problems).

