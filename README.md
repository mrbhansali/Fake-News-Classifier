# Fake News Classifier using Machine Learning

This project is a Fake News Detection system built using Natural Language Processing (NLP) and Machine Learning. It classifies news articles as real or fake based on their textual content by leveraging both vectorization techniques and various classification models.

## Project Overview

- Loaded and preprocessed a labeled news dataset  
- Converted text into numerical form using:
  - CountVectorizer
  - TF-IDF Vectorizer
- Trained and evaluated multiple machine learning models:
  - K Nearest Neighbors 
  - Multinomial Naive Bayes   
  - Random Forest Classifier
- Compared models using accuracy, confusion matrix, and classification reports

## Best Performance

Achieved 91.2% accuracy using the Random Forest Classifier with TF-IDF Vectorizer.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- CountVectorizer, TfidfVectorizer
- Matplotlib, Seaborn

## Files

- `FakeNewsClassifier.ipynb` – Full Jupyter Notebook with all preprocessing, modeling, and evaluation steps

## Results Summary

| Model           | TF-IDF Accuracy (%) | CountVectorizer Accuracy (%) |
|----------------|---------------------|-------------------------------|
| Naive Bayes     | 78.7                | 90.3                          |
| Random Forest   | 91.2                | 90.97                         |
| K-Nearest Neighbors | 49.2           | 73.8                          |


