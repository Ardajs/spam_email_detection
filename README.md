# spam_email_detection
Hybrid Machine Learning model for spam email detection using TF-IDF features and ensemble classifiers (Naive Bayes, Logistic Regression, and SVM).

# Spam Email Detection with Hybrid Machine Learning

This project implements a spam email detection system using Natural Language Processing (NLP) and machine learning techniques.

The model analyzes email text and classifies messages as **Spam** or **Ham (Not Spam)**.

The project demonstrates a hybrid approach by combining multiple machine learning models to improve classification performance.

---

## Project Overview

Email spam is one of the most common problems in digital communication. Machine learning techniques can automatically detect spam emails by learning patterns from labeled datasets.

In this project:

- Email text is processed using **TF-IDF vectorization**
- Multiple machine learning models are trained
- A **hybrid ensemble model** combines predictions

---

## Dataset

The dataset used in this project is the **Spam SMS Collection Dataset**, which contains labeled messages:

- Spam
- Ham (Not Spam)

Dataset columns:

- `label` → spam / ham
- `text` → message content

Example:

| Label | Message |
|------|------|
| ham | Hey, are we still meeting today? |
| spam | Congratulations! You have won a prize. |

---

## Machine Learning Models

The project uses the following models:

- Multinomial Naive Bayes
- Complement Naive Bayes
- Logistic Regression
- Linear SVM

These models are combined using a **Voting Classifier** to create a hybrid prediction system.

---

## Feature Engineering

Text data is converted into numerical features using:

TF-IDF (Term Frequency – Inverse Document Frequency)

Steps:

1. Text cleaning
2. Tokenization
3. TF-IDF vectorization

---

## Model Pipeline

The machine learning pipeline includes:

1. Data loading
2. Text preprocessing
3. Feature extraction (TF-IDF)
4. Train-test split
5. Model training
6. Ensemble learning
7. Model evaluation

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

