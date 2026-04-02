# Duplicate Question Pair Detection (NLP)

This project uses Machine Learning and NLP to detect whether two questions have the same meaning.

## Problem Statement
Many users ask the same question using different wording.  
This project predicts whether two questions are duplicates.

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Streamlit
- NLP techniques

## Project Structure

Duplicate_question_pairs
│
app.py
helper.py
requirements.txt
README.md
│
data
train.csv
│
models
model.pkl
│
notebooks
EDA and feature engineering notebooks

## How to Run

Install dependencies

pip install -r requirements.txt

Run the Streamlit app

streamlit run app.py

## Dataset

Quora Question Pairs Dataset

https://www.kaggle.com/c/quora-question-pairs