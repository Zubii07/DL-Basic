# 🧠 Deep Learning Basics: ANN + Backpropagation + Gradient Descent + Regularization

This repository covers foundational deep learning concepts through three core projects and hands-on code using only Python, NumPy, and scikit-learn.

---

## 📚 Topics Covered

| **Concept**                         | **Definition**                                                                                                                                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ANN (Artificial Neural Network)** | A model inspired by the human brain, composed of layers of interconnected nodes (neurons). It learns patterns from data to make predictions or classifications.     |
| └─ **Neurons**                      | The basic computing unit that processes input data using weights and biases.                                                                                        |
| └─ **Activation Functions**         | Introduce non-linearity (e.g., ReLU, Sigmoid, Tanh), enabling neural networks to learn complex functions.                                                           |
| **Feedforward Neural Network**      | A neural network where data flows in one direction: input → hidden layer(s) → output. No loops or recursion.                                                        |
| **MLP (Multilayer Perceptron)**     | A feedforward ANN with one or more hidden layers, commonly used in classification and regression tasks.                                                             |
| **Backpropagation**                | Training algorithm that computes gradients of the loss function with respect to weights using the chain rule. It updates weights via gradient descent.              |
| **Gradient Descent**                | Optimization algorithm to minimize a loss function by iteratively updating weights in the opposite direction of the gradient.                                       |

---

## 📁 Project 1: Digit Recognition using Feedforward Neural Network

### 📊 Dataset
- `sklearn.datasets.load_digits()`
- 1,797 grayscale images (8×8 pixels) of digits (0–9)
- Features: 64 pixels per image

### 🔧 Features
- Preprocessing and normalization
- Model training using `MLPClassifier` from scikit-learn
- Accuracy evaluation
- Result visualization

### 📦 Tech Stack
- Python
- scikit-learn
- Matplotlib

---

## 📁 Project 2: Manual Backpropagation (Regression)

### 💼 Problem
Predict salary (LPA) based on **CGPA** and **Profile Score** using a manually coded neural network in NumPy.

| CGPA | Profile_Score | LPA |
|------|----------------|-----|
| 8    | 8              | 4   |
| 7    | 9              | 5   |
| 6    | 10             | 6   |
| 5    | 12             | 7   |

### ⚙️ Architecture
- Input: 2 neurons
- Hidden Layer: 2 neurons (no activation)
- Output: 1 neuron (linear output)

### 🔁 Training Logic
- Manual forward pass (dot products)
- Mean Squared Error loss
- Backpropagation to compute gradients
- Weight updates via Gradient Descent (coded from scratch)

---

## 📁 Project 3: Gradient Descent Explained & Implemented

### 🎯 Goal
Understand how gradient descent works and how to implement it from scratch and with `scikit-learn`.

### ✅ Covered Topics
- Cost Function: Mean Squared Error (MSE)
- Derivatives of weights and bias
- Manual gradient computation
- Weight updates over epochs

### 💻 Implementations
- ✅ Pure Python & NumPy
- ✅ `SGDRegressor` from `sklearn` with scaling and reverse-transform logic

### 🔍 Key Insight
> Feature scaling affects the learned parameters. To interpret them in the original input space, reverse the scaling:
> - \( w_{\text{orig}} = \frac{w}{\text{std}} \)
> - \( b_{\text{orig}} = b - \frac{w \cdot \mu}{\text{std}} \)

---

## 🎓 What You'll Learn

- How neurons work internally
- How networks learn through forward and backward passes
- Gradient descent — the core training loop
- Visual intuition behind optimization
- Practical and mathematical understanding of neural network training

---

## 🧠 Ideal For
- Beginners in Deep Learning
- Students wanting hands-on + mathematical insight
- Anyone curious how learning happens inside a neural network

---

## 🧑‍💻 Author

Built with ❤️ for self-paced learning by **Me**

---

## 🙌 Happy Learning!

