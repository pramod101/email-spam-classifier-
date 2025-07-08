# email-spam-classifier-
# 📧 Email Spam Classifier – AI Mini Project

This is a simple but effective machine learning project that classifies emails as **Spam** or **Ham (Not Spam)** using the classic **SMS Spam Collection Dataset**.

---

## 🔍 Problem Statement

With increasing volumes of email spam, manual filtering is inefficient. This project builds a model to **automatically classify email messages as spam or not** using natural language features.

---

## 📦 Dataset

- Source: UCI SMS Spam Collection (5,574 messages)
- Two classes: `spam`, `ham`

---

## 🧠 Model

- **TF-IDF Vectorizer**: Converts messages into numerical features
- **Naive Bayes Classifier**: Simple yet effective model for text classification

---

## 📊 Results

| Metric        | Score   |
|---------------|---------|
| Accuracy      | 97%     |
| Precision (spam) | 100% |
| Recall (spam) | 75%     |
| F1 Score      | 86%     |

- Confusion Matrix:

[[966 0]
[ 37 112]]

---

## ✅ Key Learnings

- TF-IDF + Naive Bayes is a strong baseline for text classification
- Recall trade-off is critical: high precision avoids blocking legit messages
- Useful for real-world email/SMS filtering pipelines

---

## 📁 Files

- `spam_classifier.ipynb` – Full working notebook
- `requirements.txt` – Install dependencies using `pip install -r requirements.txt`

---

## 💬 Next Steps

- Improve recall using ensemble models (Random Forest, XGBoost)
- Use deep learning (LSTM or Transformers)
- Deploy using Streamlit or Gradio
