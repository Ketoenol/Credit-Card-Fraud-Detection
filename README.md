# Credit-Card-Fraud-Detection
📌 Credit Card Fraud Detection
🔍 Overview

This project focuses on building a binary classification model to detect fraudulent credit card transactions.
Since fraud cases are rare compared to genuine transactions, the dataset is highly imbalanced. To address this, the project applies techniques like class weighting and Dropout layers in a deep learning model built using Keras/TensorFlow.

The goal is to create a reliable fraud detection system that minimizes false negatives (missed frauds) while keeping false positives (flagging genuine users) at an acceptable level.

📊 Dataset

The dataset contains anonymized transaction features (for privacy) and a target label:

0 → Genuine Transaction

1 → Fraudulent Transaction

Extremely imbalanced: less than 0.2% transactions are fraudulent
⚙️ Key Features

✅ Preprocessing

Standardization of numerical features

Handling class imbalance with compute_class_weight

✅ Model

Built with Keras Sequential API

Dense layers with ReLU activation

Dropout layers for regularization

Output layer with Sigmoid activation for binary classification

✅ Training

Uses class weights to counter imbalance

Trained with Adam optimizer and binary_crossentropy loss

Early stopping to avoid overfitting

✅ Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Loss curves visualization

📈 Results

The model successfully detects fraudulent transactions with high recall.

Class imbalance handled using class weights and Dropout improved generalization.

Example metrics:

Precision ≈ X%

Recall ≈ Y%

F1-score ≈ Z%
