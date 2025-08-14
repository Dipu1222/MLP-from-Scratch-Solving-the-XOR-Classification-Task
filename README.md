# 2-2-1 MLP Implementation for XOR Problem in NumPy

## Overview
This project implements a simple **2-2-1 Multi-Layer Perceptron (MLP)** from scratch using **NumPy** to solve the **XOR problem**, a classic example of a non-linearly separable dataset. The MLP has:

- **Input layer:** 2 neurons  
- **Hidden layer:** 2 neurons (sigmoid activation)  
- **Output layer:** 1 neuron (sigmoid activation)  

Training is done using **backpropagation** and **manual weight updates** with **Mean Squared Error (MSE)** loss.

---

## Features

- Forward and backward propagation implemented from scratch  
- Sigmoid activation for hidden and output layers  
- Manual gradient descent updates  
- Evaluation metrics implemented from scratch:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC Curve & AUC  
- Fully working in **Google Colab** or any Python environment with **NumPy & Matplotlib**

---

## Getting Started

### Prerequisites
- Python 3.x  
- NumPy  
- Matplotlib  

Install required packages using pip:

```bash
pip install numpy matplotlib
