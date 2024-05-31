# Multi-Class Classification Model

This repository contains code for building, training, and evaluating a multi-class classification model using the Iris dataset. The model is implemented using PyTorch and leverages various tools from scikit-learn for data handling and preprocessing.

## Introduction

This project demonstrates a simple yet effective approach to multi-class classification using a neural network. The Iris dataset, which consists of 150 samples of iris flowers categorized into three species, is used to train and evaluate the model.

## Dataset

The Iris dataset contains 150 samples with four features: sepal length, sepal width, petal length, and petal width. Each sample is labeled as one of three species: setosa, versicolor, or virginica.

## Model Architecture

The neural network used in this project consists of three fully connected layers:
1. Input layer with 4 features.
2. Hidden layer with 120 neurons.
3. Hidden layer with 10 neurons.
4. Output layer with 3 neurons (one for each class).

Activation functions and optimizers are used to train the model over 1000 epochs.
