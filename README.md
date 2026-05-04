# 🎬 IMDB Movie Review Sentiment Analysis

## 📌 Project Overview

This project is a **Machine Learning-based Sentiment Analysis system** that classifies IMDB movie reviews as **Positive** or **Negative** using Natural Language Processing (NLP).

The main idea of this project is to understand how machine learning can analyze human language and automatically detect emotions from text data.

The model is built using:
- **TF-IDF Vectorization** (for converting text into numerical features)
- **Logistic Regression** (for classification)

The model achieves approximately **89% accuracy** on unseen test data, which shows good performance for a simple baseline NLP model.

---

## 🚀 Objective

The main objectives of this project are:

- To analyze and understand movie review sentiments
- To preprocess and clean raw text data
- To convert text into machine-readable format using NLP techniques
- To train a supervised machine learning model
- To predict whether a review is Positive or Negative
- To evaluate model performance using standard metrics

---

## 🧠 Machine Learning Workflow

This project follows a complete NLP + ML pipeline:

### 1. Data Collection
- IMDB movie review dataset is used
- Dataset contains labeled reviews (positive/negative)

### 2. Data Preprocessing
- Text cleaning and preparation
- Conversion of labels into numerical format:
  - Positive → 1
  - Negative → 0

### 3. Feature Extraction
- TF-IDF (Term Frequency - Inverse Document Frequency) is used
- Converts text into numerical vectors based on word importance

### 4. Train-Test Split
- Dataset is split into:
  - 80% Training Data
  - 20% Testing Data

### 5. Model Training
- Logistic Regression model is trained on training data
- It learns patterns between text features and sentiment labels

### 6. Model Evaluation
- Performance is checked using:
  - Accuracy Score
  - Precision
  - Recall
  - F1-Score

### 7. Prediction
- Model predicts sentiment of new unseen movie reviews

---

## 📊 Dataset

- **Dataset Name:** IMDB Movie Reviews Dataset  
- **Total Records:** 50,000 reviews  
- **Source:** IMDb movie review dataset  
- **Type:** Binary classification dataset  

### 📌 Classes:
- Positive Review (1)
- Negative Review (0)

### 📄 Dataset Structure:
| Column     | Description                  |
|------------|------------------------------|
| review     | Text of movie review         |
| sentiment  | Target label (positive/neg)  |

---

## 🛠️ Technologies Used

- Python 🐍 (Core programming language)
- Pandas (Data handling and analysis)
- Scikit-learn (Machine Learning library)
- NLP (Natural Language Processing concepts)
- TF-IDF Vectorizer (Feature extraction technique)
- Logistic Regression (Classification algorithm)

---

## 📦 Installation

To run this project, install the required Python libraries:

```bash
pip install pandas scikit-learn kagglehub
