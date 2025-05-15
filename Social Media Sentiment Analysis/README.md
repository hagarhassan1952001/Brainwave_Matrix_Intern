# Social Media Sentiment Analysis

This project was developed as part of my internship at **Brainwave Matrix Solutions**.  
It focuses on analyzing sentiment in Twitter data using Natural Language Processing (NLP) techniques and machine learning models to classify public opinion toward various topics.

---

## 📌 Objective

The main goal of this project is to:
- Analyze Twitter data to understand public sentiment.
- Use NLP to preprocess and clean tweets.
- Train models to classify tweets as **positive** or **negative**.
- Visualize sentiment trends over time.

---

## 📂 Dataset

- **Name:** Sentiment140 Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Details:**
  - ~1.6 million tweets.
  - Labels:  
    - `0` = Negative  
    - `2` = Neutral (ignored in our analysis)  
    - `4` = Positive  
  - Data includes tweet text, date, and other metadata.

---

## 🔧 Tools & Libraries Used

- **Python** (Google Colab)
- **Pandas** & **NumPy**
- **NLTK** – for stopwords, lemmatization
- **scikit-learn** – for vectorization and ML models
- **Matplotlib / Seaborn** – for data visualization

---

## 🧹 Preprocessing Steps

- Remove URLs, mentions, hashtags, special characters.
- Convert text to lowercase.
- Remove stopwords.
- Apply lemmatization.
- Vectorize text using `CountVectorizer`.

---

## 🧠 Models Used

### 1. **Multinomial Naive Bayes**
- Lightweight and fast.
- Accuracy: ~75%

### 2. **Logistic Regression**
- More robust, better performance on larger data.
- Accuracy: ~75%
- Evaluated using classification report and confusion matrix.

---
### 3. **Support Vector Machine**


## 📊 Evaluation Metrics

- **Accuracy**
- **Precision, Recall, F1-Score**
- **Confusion Matrix**


