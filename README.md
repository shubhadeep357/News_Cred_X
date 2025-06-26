# 🧠 News_Cred_X: Fake News Detection using NLP and Machine Learning

News_Cred_X is a machine learning-based system designed to classify news articles as **real or fake**. 
Using Natural Language Processing (NLP) techniques, it analyzes text patterns, frequencies, and semantics 
to identify credibility based on historical data.

This project serves as a foundational step toward combating misinformation using artificial intelligence.

---

## 🚀 Project Highlights

- Built using **TF-IDF Vectorization** and **Logistic Regression**
- Dataset includes over **44,000+ news articles**
- Full pipeline: Data Cleaning → Preprocessing → Vectorization → Model Training → Evaluation
- Visualization through a **Confusion Matrix**
- Easily extendable with deep learning or web deployment

---

## 📁 Dataset

The dataset is sourced from Kaggle:  
**[Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)**

It consists of two CSV files:
- `Fake.csv` – News articles labeled as fake (0)
- `True.csv` – News articles labeled as real (1)

Both datasets include columns like:
- `title`
- `text`
- `subject`
- `date`

---

## 📊 Features Used

- `text` content of each article (cleaned and normalized)
- TF-IDF features to capture the importance of each word in context
- Label: `0 = Fake`, `1 = Real`

---

## 🧠 Model Used

- **TF-IDF (Term Frequency-Inverse Document Frequency)** for text vectorization
- **Logistic Regression** for binary classification

> 🧪 Achieved over **93–96% accuracy** with strong F1 scores.

---

## 🧪 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

> Visual analysis helps understand model strengths & false positive/negative cases.

---

## 📊 Output Example

