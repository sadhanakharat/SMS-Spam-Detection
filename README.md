# 📧 Spam Detection using LSTM

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

An LSTM-based neural network for detecting spam in SMS messages! 🚀 This project preprocesses messages, trains a robust model, and accurately predicts whether a message is **Spam** or **Not Spam**.

---

## 🎯 Features

✅ Preprocessing:
- Removes special characters, numbers, and common stopwords while retaining key spam indicators (e.g., "won," "free").

✅ Model:
- Utilizes an **LSTM network** with embedding layers to understand the context of text messages.

✅ Dataset Handling:
- Balances data using **SMOTE** to improve spam detection accuracy.

✅ Evaluation:
- Reports accuracy, precision, recall, and F1 scores to assess model performance.

---

## 📂 Project Structure

```plaintext
├── spam_detection.py  # Main script
├── train.csv          # Dataset
└── README.md          # Project documentation

