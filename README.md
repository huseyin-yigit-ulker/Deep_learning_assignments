# 🧠 Deep Learning & Neural Network Foundations

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/Deep%20Learning-PyTorch%20%7C%20TorchVision-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Academic](https://img.shields.io/badge/Hacettepe%20University-Computer%20Engineering-990000.svg)](https://cs.hacettepe.edu.tr/)

**Comprehensive implementations and empirical investigations of foundational Machine Learning and Deep Learning architectures: KNN, Support Vector Machines (SVM), Multi-Layer Perceptrons (MLP), and Convolutional Neural Networks (CNN) with architectural hyperparameter ablation studies.**

</div>

---

## 📌 Repository Overview

This repository contains rigorous implementations, experiments, and technical reports exploring supervised learning and deep representation learning:

1. **Assignment 1: Classical Machine Learning & Neural Network Baselines**
   - **K-Nearest Neighbors (KNN):** Implemented from scratch with Euclidean distance metrics and hyperparameter ablation on neighbor count ($k$).
   - **Support Vector Machines (SVM):** Maximum margin optimization, linear vs. RBF kernels, and $C$ regularization tuning.
   - **Multi-Layer Perceptron (MLP):** Feedforward neural network with backpropagation, gradient descent, batch normalization, and learning rate scheduling.

2. **Assignment 2: Convolutional Neural Networks (CNN) & Hyperparameter Ablations**
   - **CNN Architecture Design:** Custom convolutional layer stacking, max pooling, feature map flattening, and dense decision layers.
   - **Parameter Sensitivity Analysis:** Empirical impact of kernel filter sizes ($3\times3$ vs $5\times5$), stride, zero-padding, activation functions (ReLU, LeakyReLU), and Dropout regularization on validation convergence.

---

## 📂 Project Structure

```ascii
Deep_learning_assignments/
├── ass1/                        # Assignment 1: KNN, SVM, and Neural Networks
│   ├── Code/                    # Implementation scripts and Jupyter notebooks
│   ├── Figures/                 # Decision boundaries, ROC curves & loss plots
│   ├── Report/                  # Comprehensive academic report (.pdf)
│   └── assignment/              # Problem statements and evaluation criteria
├── ass2/                        # Assignment 2: CNN Architectures & Parameter Studies
│   ├── Code/                    # PyTorch CNN training and evaluation scripts
│   ├── Figures/                 # Feature maps, training loss & accuracy curves
│   └── Report/                  # Technical ablation report
├── Code/                        # Shared preprocessing pipelines
└── README.md                    # Project documentation
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/huseyin-yigit-ulker/Deep_learning_assignments.git
cd Deep_learning_assignments

# Install dependencies
pip install torch torchvision scikit-learn numpy pandas matplotlib jupyter
```

---

<div align="center">
Developed by <a href="https://github.com/huseyin-yigit-ulker">Hüseyin Yiğit Ülker</a>
</div>