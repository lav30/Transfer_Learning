## Project Overview

- Established benchmarks for transfer learning using chemical gas sensor data.
- Utilised pre-trained models for unbalanced data.
- Optimized several deep learning models to improve chemical gas identification.
- Achieved improved performance metrics for binary classification using pre-trained networks.

## Transfer Learning Workflow

![](TL.png)

## Project Description

An important assumption in machine learning frameworks and algorithms is that the training and test sets must have similar label distributions and that a dataset must have thousands of observations to produce a model that generalizes well. Oftentimes, real-world datasets have dissimilar label distributions and few observations to generate an effective model performance. In such cases, model performance can be improved, if the knowledge acquired through a network trained on a large dataset can be transferred successfully to smaller datasets. This project was an attempt at the proof of concept of transfer learning between gas sensor datasets where the data order is maintained during traning. Initial experimental results indicate significant improvements in model test accuracy and other performance metrics upon applying transfer learning to smaller datasets with label imbalance.

## Project Introduction

Transfer learning can be defined as the process in which the knowledge acquired through the training of one machine learning model can be applied to a similar problem, without having to retrain a new model from scratch. Trnasfer learning can be optimised for target datasets with veru few observations. In this project, datasets related to chemical gas sensors have been utilized to train classifiers using deep neural networks (DNNs) in order to apply transfer learning to smaller but similar datasets. Transfer learning methods using DNNs have been shown to improve a model’s generalization capabilities but have traditionally been applied to perform classification on image and text data and in a few instances, data from motion sensors. This project tackles the challenging task of training classifiers for sensor data for which few benchmark results exist. This is due to a lack of robust pre-trained models for binary classification, unlike pre-trained models such as ResNet and VGG-16 that are available for image classification. 


## Project Workflow

### 1. Model Development

The source dataset is the dataset from which the model weights and features are transferred from and the target dataset is used to train a model using these learned weights. The model architecture for the pre-trained model is a multi-layer perceptron (MLP) and is implemented using Keras. The basic model architecture has an input and output layer with three hidden layers in between. The hidden layer and the number of neurons increase the complexity of the network and help the model generalize better. The activation function used in the output layer is sigmoid and it computes the probability of the label belonging to a certain class.

Since this is a binary classification problem for predicting the presence or absence of CO at a particular time, the sigmoid activation function works well. All datasets are initially utilized to train standalone models and subsequently the target datasets are used to perform transfer learning. Networks trained for transfer learning have different number of layers and neurons. The standalone model for the source dataset is trained for fifty epochs to achieve high accuracy and to ensure that the model converges successfully. Training for fewer epochs might hinder model performance. The optimizer used throughout this project is the Adam optimizer and this is a gradient descent algorithm that optimizes learning rates for all parameters. Similar model architectures have been used on datasets 2 and 3 to establish standalone model performances for datasets with reduced number of observations. These standalone performances will then be compared the performance of the pre-trained model on both the datasets. The hypothesis for this project is that the pre-trained networks obtained from training on large datasets with DNNs can be utilized on much smaller datasets with improved test accuracy and other robust metrics such as precision and recall.

### 2. Results of Training using Pre-Trained Models on the Target Datasets











