# Multimodal Music Analysis

Semester project for the **Data Mining Techniques** course.

The goal of this project is to analyze and classify music genres by combining two different types of information:

- **Lyrics (Text)**
- **Audio features (MFCC)**

## Project Overview

The project includes:

- Data cleaning and preprocessing
- Selection of the Top-5 music genres
- Word2Vec and Sentence-BERT text embeddings
- PCA-based audio embeddings from MFCC features
- Exploratory Data Analysis and visualizations
- VADER sentiment analysis of song lyrics
- Song similarity using cosine similarity
- Genre classification
- Early and Late Multimodal Fusion
- K-Means clustering

## Machine Learning

Two classifiers are used:

- Logistic Regression
- Random Forest

Four approaches are compared:

1. Text-only
2. Audio-only
3. Early Fusion
4. Late Fusion

The models are evaluated using **10-fold cross-validation** with Accuracy, Precision, Recall and Macro F1-score.

The best result was achieved by **Logistic Regression with Early Fusion**, with a Macro F1-score of approximately **0.466**.

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- gensim
- Sentence Transformers
- Matplotlib / Seaborn
- VADER Sentiment
- Jupyter Notebook

## Team

- Αλεξάνδρα Ζορμπά
- Ιάσονας Καραπροδρομίδης
