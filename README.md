# CNN-on-CIFAR10

This code is on creating a basic Convolutional Neural Network using pytorch on CIFAR-10 image dataset.
# Data:
CIFAR-10 image dataset is a dataset on images of 10 different Classes.\
` airplane 	automobile	bird	 cat	 deer	  dog    frog	 horse   ship  truck`

# Implementation:
I used Pytorch libary to implement this model. Using the `nn.Module` function we can define different layers for the neural network.
This model consists of 2-Convolutinal layers and 2-hidden layers and an output layer with `Relu` as the activation function.\
Defining hyperparameters like `learning_rate`, `num_of_epochs` to improve the model performance combining with the `Batch_normalization` method.
`Cross_entropy_loss` is the loss function used in the backpropagation step. 
