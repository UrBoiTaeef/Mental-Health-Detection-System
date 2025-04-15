# Mental-Health-Detection-System
# 🧠 Mental Health Text Classifier: Detecting Anxiety & Depression using NLP

This project is a machine learning-based web application that uses **Natural Language Processing (NLP)** to detect whether a piece of text reflects signs of **anxiety or depression**. Users input text describing their emotional state, and the system classifies it, offers a confidence score, mental health tips, and support information—all through a simple web interface.

---

## 🚀 Features

- 🔍 Detects **Anxiety** and **Depression** from text input
- 🧹 NLP pipeline: stop-word removal, punctuation cleaning, tokenization
- 📊 ML models used: Logistic Regression, Naive Bayes, SVM, KNN, Random Forest, AdaBoost
- 📈 Text vectorization using TF-IDF
- 🧪 Evaluation metrics: Accuracy, Precision, Recall, F1 Score
- 🌐 Flask web application for real-time prediction
- 🧘‍♀️ Provides:
  - Model prediction with confidence score
  - Mental wellness tips
  - Helpline and counseling information

## 🧪 Methodology

This project follows a structured pipeline to detect signs of **anxiety** or **depression** from English text input using NLP and machine learning.

### 1. 🧠 Data Collection
- The dataset contains labeled text entries that indicate mental health conditions such as **anxiety**, **depression**, or **neutral**.
- These samples are collected from public sources like social media or mental health forums.

### 2. 🧹 Data Preprocessing
- Convert all text to **lowercase**
- **Remove punctuation** and special characters
- **Remove stop words** (e.g., "and", "the", "is")
- **Tokenize** text into words
- Lemmatize or stem words for normalization

### 3. 📊 Feature Extraction
- Use **TF-IDF Vectorization** to convert cleaned text into numerical features.
- This helps the model understand which words are important across the dataset.

### 4. 🤖 Model Training
- Multiple machine learning models are trained:
  - Logistic Regression
  - Naive Bayes
  - SVM (Support Vector Machine)
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - AdaBoost
- The models are evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

### 5. ✅ Model Selection
- The **best performing model** (Logistic Regression in this case) is saved and used in the live web app.


