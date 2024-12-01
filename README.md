# Spam Detection using LSTM

This project uses an LSTM (Long Short-Term Memory) neural network for spam detection in SMS messages. The model is trained to classify messages as "Spam" or "Not Spam."

---

## Features

- Preprocesses text to remove noise (special characters, numbers, and stopwords).
- Uses SMOTE (Synthetic Minority Oversampling Technique) to handle imbalanced datasets.
- Implements a sequential LSTM model with an embedding layer for effective text representation.
- Evaluates the model's performance with metrics like accuracy and a classification report.

---

## Requirements

Install the required Python packages:
```bash
pip install tensorflow pandas nltk imbalanced-learn

