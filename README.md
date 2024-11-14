# Perceptron Moons Classification with PyTorch

A binary classifier using a Perceptron model implemented in PyTorch. This project demonstrates the limitations of the Perceptron on non-linear data and visualizes the decision boundary on the "moons" dataset, providing insight into model training, loss calculation, and boundary plotting.

## Project Overview

This project implements a basic Perceptron to classify the "moons" dataset, a standard synthetic dataset for classification problems. The Perceptron model is trained on 70% of the data, with the remaining 30% used for testing. A key feature is the visualization of the decision boundary, showing the classifier's predictions over the input space.

### Key Components
- PyTorch-based model training
- Custom loss calculation and optimizer step
- Decision boundary visualization

## Dependencies

- `torch`
- `matplotlib`
- `scikit-learn`

Install dependencies with:
```bash
pip install torch matplotlib scikit-learn
