# 🧠 Handwritten Digit Recognition using Feedforward Neural Network (MLP)

This project demonstrates how to use a **feedforward neural network** (Multilayer Perceptron - MLP) to recognize handwritten digits from the `sklearn` digits dataset. It includes preprocessing, model training, evaluation, and prediction visualization.

---

| **Concept**                         | **Definition**                                                                                                                                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ANN (Artificial Neural Network)** | A model inspired by the human brain, composed of layers of interconnected nodes (neurons). It learns patterns from data to make predictions or classifications.     |
| └─ **Neurons**                      | The basic computing unit in a neural network. It receives inputs, applies weights and bias, and passes the result through an activation function to produce output. |
| └─ **Activation Functions**         | Functions like ReLU, Sigmoid, or Tanh that introduce non-linearity, enabling the network to learn complex patterns.                                                 |
| └─ **Backpropagation**              | The training algorithm that adjusts weights by propagating the error backward through the network using gradients (partial derivatives).                            |
| **MLP (Multilayer Perceptron)**     | A type of feedforward ANN with one or more hidden layers. Each layer is fully connected to the next. It's the foundation of deep learning models.                   |
| **Feedforward Neural Network**      | A neural network where information flows only in one direction: input → hidden layer(s) → output. It has no loops or cycles.                                        |


## 📊 Dataset

- **Source**: `sklearn.datasets.load_digits()`
- **Samples**: 1,797
- **Classes**: 10 (digits 0–9)
- **Input**: 8×8 grayscale images (flattened to 64 features)

---

## 🚀 Technologies Used

- Python
- Scikit-learn
- Matplotlib
- NumPy
- Pandas

---

## Happy Learning
