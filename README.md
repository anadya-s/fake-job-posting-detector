# 🕵️‍♀️ Fake Job Posting Detector

This project detects fraudulent job listings using **logistic regression**, **TF-IDF vectorization**, and **n-gram features**.

---

## 🔍 Overview

- Dataset: [Fake Job Postings Dataset (Kaggle)](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)
- Model: Logistic Regression with `class_weight='balanced'`
- Input features: Combined job `title`, `description`, `requirements`, and `company_profile`
- Vectorization: TF-IDF with unigrams & bigrams

---

## 📊 Results

| Metric         | Score     |
|----------------|-----------|
| Accuracy       | 99.7%     |
| Fake job recall| 91%       |
| Fake job precision| 100%   |



---

## 🧠 Key ML Concepts Applied

- Text preprocessing using **TF-IDF**
- Handling **imbalanced classes** using weighted loss
- Evaluating model with **precision, recall, and F1-score**
- Built fully from scratch after completing the [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)

---


