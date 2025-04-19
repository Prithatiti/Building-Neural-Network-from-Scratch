# 🧠 Neural Network from Scratch

This repository contains a step-by-step implementation of a neural network from scratch using Python and NumPy. The main goal is to understand the internals of a neural network—neurons, layers, activations, loss functions, and optimization—by building everything manually.

---

## 📂 Project Structure

### 🔹 `Part - 1 Neural Network from Scratch - Coding Neurons and Layers.ipynb`
Kickstarts the journey by explaining the concept of a **single neuron**. Demonstrates how weights, biases, and inputs interact to produce output. Includes basic visualizations to build intuition.

---

### 🔹 `Part - 2 Neural Network from Scratch - The Beauty of Numpy and Dot Product.ipynb`
Emphasizes the power of **NumPy** in neural networks. Introduces **vectorized operations** using dot products to perform computations more efficiently than nested loops.

---

### 🔹 `Part - 3 Neural Network from Scratch - Multiple Neural Network Layers and Stacking Them Together.ipynb`
Shows how to **stack multiple layers** to form a deeper network. Explains forward propagation across layers and builds an understanding of deeper architectures.

---

### 🔹 `Part - 4 Neural Network from Scratch - Implementing The Dense Layer Class in Python.ipynb`
Wraps the logic into a **modular Dense Layer class**, encapsulating weight initialization, forward pass, and bias handling using an object-oriented approach.

---

### 🔹 `Part - 5 Neural Network from Scratch - Broadcasting and Array Summation in Python.ipynb`
Explains the concept of **broadcasting** in NumPy and its importance in matrix operations, particularly in adding biases across batches and summing gradients.

---

### 🔹 `Part - 6 Neural Network from Scratch - Coding Neural Network Activation Functions From Scratch.ipynb`
Implements key **activation functions** like ReLU, Softmax, and others. Explains how activations introduce non-linearity into the network and when to use each one.

---

### 🔹 `Part - 7 Neural Network from Scratch - Coding The Cross Entropy Loss from Scratch.ipynb`
Introduces and implements the **Cross Entropy Loss** function. Discusses its significance in classification tasks and manually derives the formula for both loss and its gradient.

---

### 🔹 `Part - 8 Neural Network from Scratch - Introduction to Optimization in Neural Network Training.ipynb`
Explores basic **optimization strategies** for training:
- **Strategy 1**: Random weights and biases (fails)
- **Strategy 2**: Iterative random adjustments (shows learning)
- Applies this to a **spiral dataset**, revealing the shortcomings of naive approaches.
Sets the stage for more advanced techniques like **gradient descent**.

---

### 🔹 `Part - 9 Neural Network from Scratch -.ipynb`
Currently under development. This part will likely integrate all components into a training loop and demonstrate model learning end-to-end.

---

## 🚧 Work in Progress

Upcoming features:
- Full training loop implementation
- Backpropagation algorithm
- Accuracy evaluation
- Saving and loading trained models

---

## 🛠️ Requirements

- Python 3.x
- NumPy
- (Optional) Jupyter Notebook

Install requirements:
```bash
pip install numpy notebook
