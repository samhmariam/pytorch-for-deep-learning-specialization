# PyTorch Workflow - EMNIST Letter Detective

## Overview

This module contains a programming assignment focused on building and training a neural network to classify handwritten letters using the EMNIST dataset.

## Notebook: C1M2_Assignment.ipynb

**EMNIST Letter Detective** - A hands-on assignment that teaches you how to:

- Load and explore the EMNIST Letters dataset (124,800 training images, 20,800 test images)
- Preprocess handwritten letter images by fixing orientation, normalizing pixel values, and converting to tensors
- Build a multi-layer neural network for 26-class letter classification (a-z)
- Train and evaluate the model on unseen test data
- Apply the trained model to decode a secret handwritten message from Andrew Ng

### Key Exercises

1. **Exercise 1**: Create EMNIST data loaders for batch processing
2. **Exercise 2**: Initialize the neural network model architecture
3. **Exercise 3**: Implement the training loop for one epoch
4. **Exercise 4**: Implement model evaluation on test data
5. **Exercise 5**: Combine training and evaluation into a complete training pipeline

### Prerequisites

- Understanding of basic PyTorch concepts
- Familiarity with neural networks and image classification
- Completion of MNIST digit classification is recommended

### Helper Files

- `helper_utils.py`: Utility functions for visualization and data processing
