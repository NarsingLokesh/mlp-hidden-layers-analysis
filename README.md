# mlp-hidden-layers-analysis
Analysis of hidden layers impact on MLP using Bank dataset
# Overview
This project explores how the number of hidden layers affects the performance of a Multilayer Perceptron (MLP). Different neural network models are built and compared to understand the trade-off between model complexity and performance.

# Technique Used
 Multilayer Perceptron (MLP)
 Feedforward Neural Network
 
# Model Details:
 Hidden Layer Activation: ReLU
 Output Layer Activation: Sigmoid
 Loss Function: Binary Crossentropy
 Optimizer: Adam
 
# Dataset
 Bank Marketing Dataset
 Binary classification problem

# Objective:
Predict whether a customer will subscribe to a term deposit.

# Models Implemented

Three different architectures were tested:

 Model - Hidden Layers 
 Model 1 - 1 layer 
 Model 2 - 2 layers 
 Model 3 - 3 layers 

# Results Summary

- The 2-layer model achieved the best performance
- The 1-layer model performed well but was less accurate
- The 3-layer model showed slight overfitting

# Key Insight:
Increasing hidden layers improves learning initially, but too many layers reduce generalisation.

---

# Graphs Generated

The following graphs are included:

- Training Accuracy vs Epochs
- Validation Accuracy vs Epochs
- Loss vs Epochs
- Hidden Layers vs Accuracy
- Target Distribution (EDA)
- Age Distribution (EDA)
