# Natural Language Processing – Zomato Reviews Sentiment Analysis

This project demonstrates an end-to-end **Natural Language Processing (NLP)** pipeline to analyze restaurant reviews and predict whether the sentiment of a review is **positive or negative**.  
It focuses on text preprocessing, feature extraction, model training, and evaluation.

---

## 📌 Project Objective

The objective of this project is to convert **unstructured text data** (customer reviews) into meaningful numerical features and apply machine learning techniques to perform **sentiment analysis**.

---

## 📁 Project Overview

- Text preprocessing and cleaning
- Feature extraction using Bag of Words
- Training a sentiment classification model
- Evaluating model performance
- Predicting sentiment of unseen reviews

---

## 🧠 Why NLP?

- Text data cannot be processed directly by machine learning models
- NLP helps extract meaning from human language
- Enables sentiment analysis, opinion mining, and feedback analysis

---

## 🔹 Dataset Description

- Contains restaurant reviews as text
- Includes sentiment labels (positive / negative)
- Text data is unstructured and requires preprocessing

---

## 🔹 Text Preprocessing

### What is done:
- Removal of special characters and numbers
- Conversion of text to lowercase
- Tokenization of sentences into words
- Removal of stopwords
- Stemming of words to root form

### Why it is important:
- Removes noise from text
- Reduces vocabulary size
- Improves model accuracy

---

## 🔹 Tokenization

### Function:
- Splits sentences into individual words

### Purpose:
- Allows the model to process text word by word
- Forms the basis for feature extraction

---

## 🔹 Stopwords Removal

### Function:
- Removes commonly used words like *is, the, and*

### Purpose:
- These words do not contribute to sentiment
- Reduces unnecessary features

---

## 🔹 Stemming

### Function:
- Converts words to their root form  
  (example: loved → love, playing → play)

### Purpose:
- Treats similar words as one
- Improves generalization

---

## 🔹 Corpus Creation

### What happens:
- All cleaned reviews are stored in a single collection

### Purpose:
- Acts as the final processed input for feature extraction

---

## 🔹 Feature Extraction (Bag of Words)

### Function:
- Converts text into numerical vectors
- Creates a vocabulary of frequent words
- Represents each review as word frequency data

### Why needed:
- Machine learning models work only with numbers
- Enables mathematical processing of text

---

## 🔹 Train–Test Split

### Function:
- Splits dataset into training and testing sets

### Purpose:
- Trains the model on known data
- Tests performance on unseen data
- Prevents overfitting

---

## 🔹 Model Training

### What happens:
- A machine learning classifier is trained on text features
- Learns patterns between words and sentiment labels

### Why suitable:
- Text data is high-dimensional and sparse
- Models like Naive Bayes work efficiently for NLP tasks

---

## 🔹 Prediction

### Function:
- Predicts sentiment for new or unseen reviews

### Output:
- Positive or Negative sentiment

---

## 🔹 Model Evaluation

### Metrics Used:
- Accuracy score
- Confusion matrix

### Purpose:
- Measures how well the model performs
- Identifies correct and incorrect predictions

---

## 🔹 Confusion Matrix

### What it shows:
- True Positives
- True Negatives
- False Positives
- False Negatives

### Why important:
- Provides detailed insight into model performance

---

## 🔄 NLP Pipeline Summary

Raw Text
→ Text Cleaning
→ Tokenization
→ Stopwords Removal
→ Stemming
→ Feature Extraction
→ Model Training
→ Prediction
→ Evaluation
---

## 🌍 Real-World Applications

- Restaurant review analysis
- Product review sentiment analysis
- Customer feedback systems
- Social media opinion mining

---

## 🎯 Learning Outcomes

- Understanding of NLP preprocessing techniques
- Hands-on experience with text vectorization
- Practical exposure to sentiment analysis
- End-to-end NLP workflow implementation

---

## ⏱️ 30-Second Project Explanation

> I worked on an NLP project where I analyzed restaurant reviews using sentiment analysis. I cleaned and preprocessed the text, converted it into numerical features using Bag of Words, and trained a machine learning model to classify reviews as positive or negative. This project helped me understand how unstructured text is transformed into actionable insights.

---

## 👤 Author

**Yatnesh Sokal**

