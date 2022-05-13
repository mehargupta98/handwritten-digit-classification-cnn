# Handwritten Digit Classification using CNN

In this project, a convolutional neural network is developed for handwritten digit classification from scratch using both Tenserflow and Keras.

The goal is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

## 1. About Dataset

We have used MNIST dataset from TensorFlow

The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalised and centred in a fixed-size image.

## 2. Creating and Training a CNN
In the CNN model created, there is an input layer followed by two hidden layers, a dropout layer and finally an output layer. 

Once the model has been created, we compile it and fit the model. During the process of fitting, the model will go through the dataset and understand the relations. It will learn throughout the process as many times as has been defined. In this project, 25 epochs are defined.

## 3. Making Predictions
The above created model makes predictions for the test dataset. For each of the 10 possible digits, a probability score is calculated. The class with the highest probability score is the prediction made by the model.

## 4. Results
We get an accuracy of 98.56% on the test image data.
