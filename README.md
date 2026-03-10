# DL Assignment 4 – Sentiment Analysis

## Overview
This project focuses on building machine learning models to classify emotions in text samples. The task involves preprocessing text data, extracting meaningful features, training classification models, and comparing their performance.

---

## Objective
To develop and evaluate machine learning models for emotion classification using:

- Naive Bayes
- Support Vector Machine (SVM)

---

## Dataset
The dataset contains text samples along with their corresponding emotion labels.

---

## Project Workflow

### 1️. Data Loading & Preprocessing
- Converted text to lowercase
- Removed punctuation and numbers
- Tokenized text
- Removed stopwords

These steps help reduce noise and improve model performance by focusing on meaningful words.

---

### 2️. Feature Extraction
Used **TF-IDF (Term Frequency - Inverse Document Frequency)** to convert text into numerical feature vectors.

TF-IDF assigns higher importance to informative words while reducing the weight of frequently occurring words.

---

### 3️. Model Development
Two models were trained:

- **Multinomial Naive Bayes**
- **Support Vector Machine (Linear Kernel)**

---

### 4️. Model Evaluation
Models were evaluated using:

- Accuracy
- F1-Score (Weighted)
- Classification Report

---

## Results
- SVM generally performed better due to its effectiveness in handling high-dimensional sparse text data.
- Naive Bayes was computationally efficient and performed well for text classification.

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer

---

## 📌 Conclusion
This project demonstrates the effectiveness of machine learning techniques for emotion classification. Among the models tested, SVM achieved better performance, making it suitable for text-based emotion detection tasks.

---

##  Author
Fathima Salga  
DL Assignment 4 – Sentiment Analysis
