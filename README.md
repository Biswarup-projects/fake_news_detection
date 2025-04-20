---

# 📰 Fake News Detection using TensorFlow

A supervised machine learning project to classify news articles as **real** or **fake**, leveraging natural language processing and deep learning techniques.

## 📌 Objective

Build an accurate text classification model using TensorFlow to detect fake news articles based on their titles and content.

---

## 🧠 Model Overview

- **Model Type**: Binary text classification
- **Framework**: TensorFlow / Keras
- **Architecture**: NLP preprocessing with embedding + sequential layers (e.g., LSTM/Dense)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 📂 Dataset Overview

The dataset used for this project is a labeled collection of news articles consisting of two main components:

- **Title**: The headline of the news article  
- **Text**: The main body/content of the news article  
- **Label**: The target variable, where:
  - `1` indicates **fake news**
  - `0` indicates **real news**

### 🔢 Dataset Summary

- Format: CSV (`fake news.csv`)
- Total Rows: ~20,800+
- Features: `id`, `title`, `author`, `text`, `label`
- Missing Values: Present in some `author` and `title` fields

> The dataset offers a strong foundation to train a model that learns patterns in linguistic features distinguishing fake and real news.

---

## ⚙️ Project Workflow

1. **Data Preprocessing**  
   - Handling missing values  
   - Text cleaning (punctuation, stopwords, etc.)  
   - Tokenization & padding

2. **Model Development**  
   - Text vectorization (embedding layer)  
   - Neural network training with TensorFlow

3. **Model Evaluation**  
   - Performance on test data  
   - Metric reporting

4. **Deployment (optional)**  
   - Export model for future use

---

## 🛠️ Requirements

- Python ≥ 3.8  
- TensorFlow ≥ 2.x  
- NumPy, Pandas, Matplotlib, Scikit-learn  
- Jupyter Notebook / Google Colab

---

## 📊 Results

Model evaluation metrics are reported with a detailed confusion matrix and classification report, highlighting the model’s ability to differentiate fake vs real news.

---

## 🧠 Author
- **Biswarup Majumdar**  
- Data Science Enthusiast | [LinkedIn](https://linkedin.com/in/biswarup-majumdar)
