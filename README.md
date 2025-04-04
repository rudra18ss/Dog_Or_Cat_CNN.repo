# Dog_Or_Cat_CNN.repo
This is a CNN build on Kaggle Dataset for classification between Dog and Cat images.

# What is CNN ? :
A convolutional neural network (CNN or ConvNet) is a network architecture for deep learning that learns directly from data.
CNNs are particularly useful for finding patterns in images to recognize objects, classes, and categories.
They can also be quite effective for classifying audio, time-series, and signal data.

# About This CNN Model :
loss: 0.1275
Accuracy: 0.9452
val_loss: 0.6127
val_accuracy: 0.8090
Note : Previuos stats may change depending on your model training environment.

# CNN part :
Number of Convolutional layers used = 3, activation = "Relu", strides= 2, padding = "Valid"
Number of Pooling layers = 3, strides = 2, padding = "Valid"
Number of flatten layer = 1

# ANN PART :
One dense layer with 128 Neurons and Relu activation.
one Hidden layer with 64 Neurons Relu activationn.
one Output layer with one Neuron Sigmoid.

# Improvement techniques used :
Dropout rate = 0.1
BatchNormalization of ( 1, 256, 256, 3) per image.

# Dataset used :
Prediction for Cat = 0 and Dog = 1
New Data given for Validation of prediction = <a> https://www.kaggle.com/datasets/rajatyd/testing-data-images </a>
for Traning and Testing = <a>https://www.kaggle.com/datasets/salader/dogs-vs-cats</a>

