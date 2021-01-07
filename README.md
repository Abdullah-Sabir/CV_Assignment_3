# CV_Assignment_3
# Intel-Image-Classification
Building a powerful Neural network that can classify Natural Scenes around the world
# Description
Implement an image classification pipeline using CNN to classify the natural scenes images into different
classes. we can use CNN architecture of your own choice, i.e. build VGG, or ResNet style
architecture using primitive layers or call in the pre-implemented architecutes available in Keras /
Pytorch.
The goal is to classify images under 6 categories. {'buildings' -> 0, 'forest' -> 1, 'glacier' -> 2, 'mountain' -> 3, 'sea' -> 4, 'street' -> 5 }. The dataset is available for download at https://www.kaggle.com/puneet6060/intel-image-classification.
# Model Arhitecture
![alt text](https://miro.medium.com/max/470/1*3-TqqkRQ4rWLOMX-gvkYwA.png)
# Model
The model we have chosen for our implementation is VGG. VGG is an architecture of convolutional neural network which took home the gold for the 2014 competition of image net. Even in 2021, this architecture is still considered state of the art because instead of increasing layers and hyperparameters, this implementation focusses on the convolution of 3x3 and having with stride=1 with the similar padding condition for feature map and input image which is all pooled together with 2x2 filter and 2 as its stride. The pooling, which is used in this model, is called max pooling. This placement of Conv layers and pooling layers is followed throughout the model, and the implementation is concluded with two fully connected layers of 4096 neurons and ends with an output layer consisting of # of neurons, each representing a class.
# Code
Code is self explanatory so you shouldn't have any problem
# Pre-Train Weighs
Pre-Train Weighs are also included to simulate similiar kind of performance
