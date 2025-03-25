# Handwritten Digit Recognition with Neural Networks

A simple PyTorch project that trains a Multilayer Perceptron (MLP) to recognize handwritten digits from the MNIST dataset. It includes training, evaluation, visualization of results, and an option to predict on external images.

## Project Overview

**Goal:** Classify 28×28 images of handwritten digits (0–9) with high accuracy.

### Approach

- Use the MNIST dataset for training and testing  
- Build an MLP model with fully‑connected layers and ReLU activations  
- Train using the Adam optimizer and CrossEntropyLoss  
- Evaluate performance using accuracy and a confusion matrix  
- (Optional) Predict custom handwritten digit images  

## Features

### Data Loading & Preprocessing

- Automatically downloads MNIST  
- Normalizes images for consistent training  

### Model Training & Evaluation

- Prints training loss and accuracy per epoch  
- Computes test accuracy and generates a confusion matrix  

### Visualization

- Plots training loss and accuracy curves with Matplotlib  
- Displays a confusion matrix for class‑wise performance  

### External Image Prediction (Optional)

- Loads and preprocesses custom digit images  
- Outputs predicted digit after running inference with the trained model  

