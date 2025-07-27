# 🧠 Artificial Neural Network (ANN) for Classification

This project implements a deep learning classification model using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras. The goal is to classify data based on multiple features using a feedforward neural network, while applying regularization techniques to reduce overfitting and improve generalization.

---

## 🧬 Dataset Overview

- **Type**: Structured tabular data  
- **Task**: Classification (Binary or Multi-class)  
- **Features**: Numerical and/or categorical  
- **Target**: Class label (e.g., 0/1 or one-hot encoded)  
- **Source**: *(Mention dataset source or leave blank if private)*

---

## 🧠 Model Summary

The ANN model includes the following components:

- **Input Layer**: Based on the number of input features

- **Hidden Layers**:
  - Dense layers with ReLU activation
  - Dropout layers for regularization
  - Batch Normalization for stable and faster training
  - L2 regularization (kernel regularizer) to reduce overfitting

- **Output Layer**:
  - `sigmoid` activation for binary classification
  - `softmax` activation for multi-class classification

- **Loss Function**:
  - `binary_crossentropy` or `categorical_crossentropy`

- **Optimizer**: Adam

- **Metrics**: Accuracy

- **Callbacks**:
  - EarlyStopping (monitors validation loss, with patience and best weights restored)

---

## 🧪 Techniques Applied

- ✅ Dropout Regularization  
- ✅ Batch Normalization  
- ✅ L2 Weight Regularization  
- ✅ Early Stopping with best weight restoration  
- ✅ Learning Rate Tuning  
- ✅ Feature Scaling  
- ✅ Train/Test or Stratified Validation Split

---

## 📈 Results

- **Training Accuracy**: Reaches ~100%  

- **Testing Accuracy**: Around ~50–52%  

- **Observation**: Model overfits quickly despite using regularization techniques. Indicates the need for either more data, better features, or a different model architecture.

---

