# 🎬 IMDb Movie Review Sentiment Classifier

This project builds a sentiment analysis model to classify IMDb movie reviews as **positive** or **negative** using natural language processing (NLP) techniques and machine learning.

## 🚀 Overview

- NLP preprocessing with NLTK
- Feature extraction using TF-IDF
- Classification using Logistic Regression
- Optional: LSTM deep learning model with Keras
- Dataset: IMDb Large Movie Review Dataset

## 📁 Dataset

Download from: [IMDb Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

- 25,000 training reviews
- 25,000 testing reviews
- Labeled as `pos` or `neg`

## 🔧 Technologies Used

- Python
- NLTK / spaCy
- Scikit-learn
- Keras / TensorFlow (optional)
- Matplotlib / Seaborn

## 📊 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 88%      |
| Naive Bayes         | 85%      |
| LSTM (Keras)        | 90%      |

## 📦 How to Run

```bash
pip install -r requirements.txt
python main.py
