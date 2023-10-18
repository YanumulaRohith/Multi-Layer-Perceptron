# Handwritten Digit Recognition with Multi-Layer Perceptron (MLP)
This repository contains a Python script that implements a Multi-Layer Perceptron (MLP) using the Keras library. The model is trained on the MNIST dataset to recognize handwritten digits. After training the model for 50 epochs with a batch size of 128, the test accuracy achieved is 97.26%.

## Overview
In this project, a Multi-Layer Perceptron neural network is employed to recognize handwritten digits from the MNIST dataset. The MNIST dataset is a popular dataset in the machine learning community, consisting of 28x28 grayscale images of handwritten digits (0 through 9) and their corresponding labels.
## Model Architecture
The MLP model used in this project has the following architecture
Model: "sequential_1"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_3 (Dense)             (None, 512)               401920    
                                                                 
 dropout_2 (Dropout)         (None, 512)               0         
                                                                 
 dense_4 (Dense)             (None, 512)               262656    
                                                                 
 dropout_3 (Dropout)         (None, 512)               0         
                                                                 
 dense_5 (Dense)             (None, 10)                5130      
                                                                 
=================================================================
Total params: 669706 (2.55 MB)
Trainable params: 669706 (2.55 MB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________

## Results
After training the model for 50 epochs with a batch size of 128, the test accuracy achieved is approximately 97.26%.
