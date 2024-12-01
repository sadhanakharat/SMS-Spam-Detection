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

## 📊 Dataset

The dataset should be in CSV format (`train.csv`) with the following structure:

| Column Name | Description                                      |
|-------------|--------------------------------------------------|
| `sms`       | The text message content                         |
| `label`     | `1` for spam, `0` for non-spam (ham)             |

 **Example Dataset**
CSV
sms,label
"Congratulations! You've won a $1000 Walmart gift card!",1
"Hi, how are you?",0
"Claim your free prize now!",1
"Let's meet up this weekend.",0

---

## 📈 Performance Metrics

The model’s performance is evaluated based on the following metrics:

| Metric       | Value  |
|--------------|--------|
| **Accuracy** | 95.2%  |
| **Precision**| 92.8%  |
| **Recall**   | 93.5%  |
| **F1-Score** | 93.1%  |

These metrics indicate the model's effectiveness in detecting spam, with a good balance between precision and recall.
## 📬 Contact

For questions, suggestions, or collaboration, feel free to reach out:

- **Email**: Kharatsadhana22@example.com
- **GitHub**: [sadhanakharat](https://github.com/sadhanakharat)

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.



```

## 📂 Project Structure

```plaintext
├── spam_detection.py  # Main script
├── train.csv          # Dataset
└── README.md          # Project documentation



