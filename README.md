# Digit-Recognition-MNIST-Dataset-with-Keras

  The Dataset consists of 28 x 28 greyscale images of handwritten digits (0 through 9). And our goal is to identify the digit. There are 60,000 training examples (of which, the first 10,000 I've chosen to be validation set), and further 10,000 test examples.

  I've implemented two different Neural Networks. First implementation (MNIST_9580.ipynb) consists of only fully-connected layers (Dense Layers). Regularization is used to fight overfitting. This gives a **95.8% accuracy** on test set (28 epochs).
In the second attempt (MNIST_9914.ipynb), ConvNets are used, which give **99.14% accuracy** on test set (20 epochs). Dropout is used here to overcome overfitting.

  All implementations are made using **Keras**. This example was inspired by the book **Deep Learning with Python** written by Keras author Francois Chollet.
  
  The files are created in Google Colab. Link is included.
  
  This is my first repository on Github. Comments and Suggestions are welcome!
  
  Author: Raahat Gupta
  Date: 22/08/2018
