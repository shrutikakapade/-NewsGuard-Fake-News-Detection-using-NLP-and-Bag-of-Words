# 🧠 NewsGuard: Fake News Detection using NLP and Bag of Words

## 📌 Project Description
**NewsGuard** is an intelligent NLP-driven solution that uses the **Bag of Words** approach to detect and classify fake news articles. Built to combat the spread of misinformation, this project analyzes news content and predicts whether an article is *real* or *fake*, empowering platforms to maintain information integrity.

---

## 🔍 Problem Statement
With the rapid spread of unverified news across digital platforms, distinguishing real news from fake has become critical. This project aims to develop a machine learning pipeline that can automatically detect fake news based on textual content.

---

## 🗂️ Dataset
The dataset contains two CSV files:

- `True.csv` – Real news articles  
- `Fake.csv` – Fake news articles

**Columns include:**
- `title` – Headline of the article  
- `text` – Full article content  
- `subject` – Topic category  
- `date` – Publication date  

A new column `label` was added:
- `1` for real news  
- `0` for fake news

---

## 🧪 Technologies Used
- Python  
- Pandas, NumPy  
- NLTK, Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## 🧱 Project Workflow

### 1. Data Preparation
- Load and label data
- Merge datasets and shuffle

### 2. Data Cleaning
- Lowercasing, punctuation & HTML removal
- Tokenization, stopword removal
- Lemmatization
- Save cleaned text as `clean_content`

### 3. Exploratory Data Analysis (EDA)
- Label distribution plots
- Word frequency comparison
- Word clouds and n-grams

### 4. Feature Extraction
- Vectorization using **Bag of Words** (CountVectorizer)

### 5. Model Building
- Train-test split (e.g., 80/20)
- Model training using a classifier (e.g., Naive Bayes)

### 6. Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix and ROC Curve

### 7. Error Analysis & Insights
- Misclassified examples
- Keyword patterns in fake vs real news

---

## 📊 Results
- Achieved strong accuracy in detecting fake news
- Identified top contributing words for each class
- Balanced performance in real-world scenarios

