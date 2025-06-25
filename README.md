# 🧠 Deep Learning Basics: Feedforward Neural Network + Manual Backpropagation

This repository demonstrates foundational deep learning concepts with two hands-on projects:

1. **Handwritten Digit Recognition** using a feedforward neural network (MLP)
2. **Manual Backpropagation** from scratch using NumPy — applied to a mini regression dataset

Both projects build intuition around how neural networks operate and how weights are adjusted using backpropagation.

---

## 🧠 Core Concepts

| **Concept**                         | **Definition**                                                                                                                                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ANN (Artificial Neural Network)** | A model inspired by the human brain, composed of layers of interconnected nodes (neurons). It learns patterns from data to make predictions or classifications.     |
| └─ **Neurons**                      | The basic computing unit in a neural network. It receives inputs, applies weights and bias, and passes the result through an activation function to produce output. |
| └─ **Activation Functions**         | Functions like ReLU, Sigmoid, or Tanh that introduce non-linearity, enabling the network to learn complex patterns.                                                 |
| └─ **Backpropagation**              | The training algorithm that adjusts weights by propagating the error backward through the network using gradients (partial derivatives).                            |
| **MLP (Multilayer Perceptron)**     | A type of feedforward ANN with one or more hidden layers. Each layer is fully connected to the next. It's the foundation of deep learning models.                   |
| **Feedforward Neural Network**      | A neural network where information flows only in one direction: input → hidden layer(s) → output. It has no loops or cycles.                                        |

---

## 📁 Project 1: Handwritten Digit Recognition using Feedforward Neural Network (MLP)

### 📊 Dataset
- **Source**: `sklearn.datasets.load_digits()`
- **Samples**: 1,797
- **Classes**: 10 (digits 0–9)
- **Input**: 8×8 grayscale images (flattened to 64 features)

### 📌 Features
- Preprocessing and normalization
- Training with `MLPClassifier` (sklearn)
- Accuracy scoring
- Visualization of predictions

### 📦 Technologies
- Python
- Scikit-learn
- Matplotlib
- NumPy

---

## 📁 Project 2: Manual Backpropagation (Regression Task)

### 🧪 Problem
Predict salary (`LPA`) using two input features: **CGPA** and **Profile Score**.

### 📊 Sample Data

| CGPA | Profile_Score | LPA (Target) |
|------|----------------|--------------|
| 8    | 8              | 4            |
| 7    | 9              | 5            |
| 6    | 10             | 6            |
| 5    | 12             | 7            |

### ⚙️ Model Architecture
- **Input layer**: 2 neurons
- **Hidden layer**: 2 neurons
- **Output layer**: 1 neuron
- No activation functions used (pure linear layers)

### 🧮 Training Flow
- Manual forward propagation using matrix dot products
- Manual loss computation (mean squared error)
- Manually derived gradient updates using backpropagation logic
- Trained over multiple epochs to minimize loss

### ✨ Highlights
- All implemented with **NumPy only**
- Great for educational use
- Shows how weight adjustments happen mathematically

---

## ✅ What You’ll Learn
- How data flows through a neural network (forward pass)
- How errors are measured and propagated backward (backpropagation)
- The effect of weight updates across epochs
- Real-world application of ANN in both classification and regression

---

## 🧑‍💻 Author
Built with ❤️ for learning by Me

---

## 🙌 Happy Learning!
