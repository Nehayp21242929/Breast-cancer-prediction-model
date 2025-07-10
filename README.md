# Breast-cancer-prediction-model
# 🧠 Binary Classification with PyTorch

This is a simple machine learning project where I built and trained a **binary classification model** using **PyTorch**. It’s meant to demonstrate how deep learning works at a basic level — from building the model to training it and saving it for future use.

The dataset is very simple: just two numerical features and a binary label (`0` or `1`). But it's a great way to learn how neural networks work behind the scenes!

---

## 🚀 What This Project Does

- Builds a small feedforward neural network using PyTorch
- Trains the model on a simple 2D dataset
- Tracks loss and accuracy during training
- Saves the trained model (`model.pth`) for later use
- (Optional) Visualizes the decision boundary

---

## 🧱 How the Model is Structured

The model is built using PyTorch’s `nn.Sequential` and includes:

- **Input Layer**: 2 features
- **Hidden Layer**: 16 neurons with ReLU activation
- **Output Layer**: 1 neuron with Sigmoid activation (for binary classification)

It’s optimized using the **Adam** optimizer and trained using **Binary Cross-Entropy Loss**.
