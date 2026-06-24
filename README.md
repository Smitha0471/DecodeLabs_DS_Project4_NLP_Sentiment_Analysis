# DecodeLabs_DS_Project4_NLP_Sentiment_Analysis

## Project Overview

This project focuses on Natural Language Processing (NLP) and Sentiment Analysis. The objective is to build a machine learning model capable of understanding and classifying human text reviews as Positive or Negative.

The project demonstrates how unstructured text data can be transformed into meaningful numerical representations and analyzed using machine learning algorithms.

---

## Project Objective

* Build a complete NLP preprocessing pipeline.
* Clean and prepare unstructured text data.
* Convert text into numerical features using TF-IDF.
* Train a machine learning model for sentiment classification.
* Predict whether a review expresses positive or negative sentiment.

---

## Dataset

Dataset Used: IMDb Movie Reviews Dataset

The dataset contains movie reviews along with their corresponding sentiment labels.

### Features

* Review → Text review written by users
* Sentiment → Positive or Negative

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab

---

## Project Workflow

### 1. Data Loading

* Imported the IMDb movie review dataset.
* Explored dataset structure and sentiment distribution.

### 2. Text Preprocessing

A complete NLP preprocessing pipeline was implemented:

#### Tokenization

Text was broken into individual words.

#### Lowercasing

All text was converted to lowercase.

#### Stop-Word Removal

Common words with little semantic value were removed.

Examples:

* the
* is
* and
* was

#### Lemmatization

Words were reduced to their root form.

Examples:

* running → run
* studies → study

#### Special Character Removal

Numbers, punctuation, and unnecessary symbols were removed.

---

### 3. TF-IDF Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert text into mathematical feature vectors.

Benefits:

* Captures important words
* Reduces influence of common terms
* Creates machine-readable numerical representations

---

### 4. Model Training

A Multinomial Naive Bayes classifier was trained on the TF-IDF features.

Why Naive Bayes?

* Fast and efficient
* Performs well on text classification tasks
* Commonly used in sentiment analysis

---

### 5. Model Evaluation

The model was evaluated using:

* Classification Report
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

### 6. Sentiment Prediction

The trained model was tested on new unseen reviews and successfully predicted whether the sentiment was:

* Positive
* Negative

---

## Key Skills Demonstrated

* Natural Language Processing (NLP)
* Text Cleaning
* Tokenization
* Stop-Word Removal
* Lemmatization
* TF-IDF Vectorization
* Machine Learning for Text Classification
* Sentiment Analysis
* Unstructured Data Handling

---

## Results

Successfully built a sentiment analysis system capable of classifying movie reviews into positive and negative categories using machine learning techniques.

The NLP pipeline transformed raw human language into structured numerical data suitable for machine learning.

---

## Conclusion

A complete NLP and Sentiment Analysis pipeline was developed. Text preprocessing, TF-IDF vectorization, and Naive Bayes classification were successfully implemented to analyze and predict human sentiment from unstructured text data.

This project demonstrates how Natural Language Processing can be used to extract meaningful insights from textual information and support data-driven decision making.

---

## Author

Smitha 

---

## Internship

DecodeLabs Data Science Internship – Week 4 Project
