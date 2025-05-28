# 🧠 Handwritten Digit Classifier using PyTorch


---

## 🚀 Project Overview

This project demonstrates how to build, train, and evaluate a deep learning model using PyTorch to classify handwritten digits from the well-known MNIST dataset. It covers all essential steps including data loading, preprocessing, model architecture design, training, hyperparameter tuning, evaluation, and saving the trained model for future use.

---

## 🔍 Features

- Load and preprocess the MNIST dataset using `torchvision`
- Visualize and explore the dataset to understand data distribution and preprocessing needs
- Design a fully connected neural network (FCNN) with multiple hidden layers and dropout for regularization
- Train the model using the Adam optimizer and cross-entropy loss
- Achieve high test accuracy of **98.06%** after hyperparameter tuning
- Save the trained model state for easy reuse without retraining

---

## 🛠 Model Architecture

- Fully Connected Neural Network (FCNN)
- Layers:
  - Input (784) → Hidden Layer 1 (256)
  - Hidden Layer 1 (256) → Hidden Layer 2 (128)
  - Hidden Layer 2 (128) → Hidden Layer 3 (64)
  - Hidden Layer 3 (64) → Output Layer (10 classes)
- Activation: ReLU
- Dropout: 20%
- Loss function: CrossEntropyLoss
- Optimizer: Adam with learning rate 0.0005

---

## 📈 Performance

- Trained for 15 epochs
- Achieved final test accuracy of **98.06%**

---

## 💻 How to Run

1. Install the required packages:
   ```bash
   pip install -r requirements.txt

## 📂 Repository Contents

| File                          | Description                                    |
|-------------------------------|------------------------------------------------|
| `MNIST_Handwritten_Digits.ipynb` | Jupyter notebook with full code and training steps |
| `MNIST_Handwritten_Digits.pth`   | Saved PyTorch model weights after training      |
| `requirements.txt`              | List of Python dependencies needed for the project |

---

## 📚 Requirements

- Python  
- PyTorch  
- torchvision  
- matplotlib  
