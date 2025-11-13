# NLP_Project

Live Web Link : https://swapnil-nlp-duplicate-question-detector.streamlit.app/

This project identifies whether two input questions are semantically similar or duplicates — inspired by the Quora Question Pair challenge.

Features:
Built using Python, Streamlit, and scikit-learn

Uses text preprocessing, feature engineering,Advance Preprocessing and Bag-of-Words.

Applies a trained Random Forest classifier for prediction

Web app built with Streamlit for interactive user input

Tech Stack:
,scikit-learn
,nltk
,fuzzywuzzy
,pickle (for model storage)

How It Works:
User enters two questions.
Features are extracted (length, overlap, fuzzy scores, etc.).
Questions are vectorized using CountVectorizer.
Prediction is made using the trained ML model.
Output: Whether the questions are duplicates or not.
