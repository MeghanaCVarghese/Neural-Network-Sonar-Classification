# 🔥 Neural Networks (ANN) - Sonar Signal Classification

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-ANN-red)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange?logo=tensorflow)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Dataset](https://img.shields.io/badge/Dataset-Sonar-blueviolet)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Project Overview
This project implements an **Artificial Neural Network (ANN)** to classify sonar signals as either **Mines (M)** or **Rocks (R)**.

The dataset consists of 60 numerical features representing sonar signal energy levels across different frequency bands. The model is built using **TensorFlow/Keras** and evaluated using multiple performance metrics.

---

## 🎯 Problem Statement
Classify underwater sonar signals into:
- **Mine (M)** → Metallic object (dangerous)
- **Rock (R)** → Natural object (safe)

This problem is important in:
- Maritime safety 🚢  
- Naval defense ⚓  
- Underwater object detection 🌊  

---

## 📊 Dataset Information
- Total Samples: **208**
- Features: **60 numerical features**
- Target Variable:
  - `M` → Mine
  - `R` → Rock

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 🔍 Data Preprocessing
- Label Encoding (M → 1, R → 0)
- Feature Scaling using **StandardScaler**
- Train-Test Split (80-20)

---

## 🧠 ANN Model Architecture
- Input Layer: 60 neurons
- Hidden Layer 1: 32 neurons (ReLU)
- Dropout Layer: 0.2
- Hidden Layer 2: 16 neurons (ReLU)
- Output Layer: 1 neuron (Sigmoid)

---

## ⚙️ Model Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Epochs: 100
- Batch Size: 8

---

## 📈 Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📊 Visualizations
- Feature Distribution (Histograms)
- Boxplots (Outlier Detection)
- Confusion Matrix
- Training vs Validation Accuracy
- Training vs Validation Loss

---

## 📌 Results
- The ANN model successfully classifies sonar signals with strong performance.
- Dropout helps reduce overfitting.
- Feature scaling significantly improves model convergence.

---

## 💡 Key Learnings
- Importance of feature scaling in neural networks
- How ANN learns complex patterns from data
- Role of activation functions (ReLU, Sigmoid)
- Preventing overfitting using Dropout
- Evaluating classification models using multiple metrics

---

## 👩‍💻 Author

Meghana C Varghese
