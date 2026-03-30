# 🎯 Customer Support Ticket Classification & Priority Prediction

## 📌 Overview
This project is an NLP-based Machine Learning system that automatically classifies customer support tickets and assigns priority levels.

It helps organizations:
- 📂 Categorize tickets (Billing, Technical, Account, General)
- ⚡ Identify urgent issues
- 🚀 Improve response time and efficiency

---

## 🧠 Problem Statement
Manual handling of support tickets is slow and inefficient.  
This project automates:
- Ticket classification  
- Priority detection  
- Support workflow optimization  

---

## 🛠️ Tech Stack
- Python  
- Jupyter Notebook  
- Scikit-learn  
- NLTK  

---

## 📊 Dataset
- Customer Support Ticket Dataset (Kaggle)
- Includes:
  - Ticket text
  - Category labels

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Lowercasing
- Removing punctuation
- Stopword removal

### 2. Feature Extraction
- TF-IDF Vectorization

### 3. Model Building
- Logistic Regression

### 4. Priority Assignment
- Rule-based logic:
  - "urgent", "asap" → High
  - "issue", "problem" → Medium
  - Others → Low

---

## 🔄 Workflow
Raw Text → Cleaning → TF-IDF → Model Training → Prediction → Priority Assignment

---

## ✨ Key Features
- Automated ticket classification
- Priority prediction system
- NLP preprocessing pipeline
- Easy to understand and scalable



