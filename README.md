# Duplicate Question Pair Detection (NLP)

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to detect whether two questions have the same meaning (duplicate) or not.

The model analyzes two questions and predicts if they are semantically similar.

---

## 🚀 Demo

User enters two questions →  
Model predicts:

Duplicate ✅  
Not Duplicate ❌

---

## 📌 Problem Statement

Platforms like Quora have millions of questions, and many users ask the same question in different wording.  
This project detects duplicate questions automatically to reduce redundancy and improve search results.

---

## 📊 Dataset

Dataset used: **Quora Question Pairs Dataset**

Features in dataset:

- id – question pair id  
- qid1, qid2 – unique question ids  
- question1 – first question  
- question2 – second question  
- is_duplicate – target label (1 = duplicate, 0 = not duplicate)

---

## 🧠 Approach

Steps followed in this project:

1. Data preprocessing
2. Feature engineering
3. Text similarity features
4. Bag of Words (BoW)
5. Machine Learning model training
6. Prediction using Streamlit web app

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- FuzzyWuzzy
- Streamlit
- NLP techniques

---

## 📂 Project Structure

Dataset: https://www.kaggle.com/c/quora-question-pairs