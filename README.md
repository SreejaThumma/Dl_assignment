# Dl_assignment
# Fashion MNIST Classification Project
# Overview
This project classifies images from the Fashion MNIST dataset using neural networks with different settings.
# Requirements
Install the required libraries:
torch
torchvision
matplotlib
numpy
kagglehub
# Dataset
Training Data: 60,000 images
Test Data: 10,000 images
# Model Training
The model supports:
Hidden Layers: [128, 64], [128, 64, 32], [64, 32]
Activations: ReLU and Sigmoid
Optimizers: Adam, RMSprop, SGD, MGD, NGD
Weight Initialization: Xavier Initialization
To train the model, run:
python train.py
# Evaluation
To evaluate the model, run:
python evaluate.py
The best model is selected based on accuracy.
# Results
[128, 64] + ReLU + RMSprop → 87.00%
[128, 64, 32] + ReLU + Nesterov Momentum → 87.11%
[64, 32] + ReLU + Adam → 86.85%
# Key Learnings
ReLU performs better than Sigmoid.
Adam and RMSprop optimizers yield better accuracy.
Networks with 2-3 hidden layers balance accuracy and generalization.
# Conclusion
This project highlights the impact of hyperparameters on image classification performance.
