# 🎬 IMDb Movie Review Sentiment Analysis using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-2ECC71?style=for-the-badge)
![TF-IDF](https://img.shields.io/badge/TF--IDF-Feature%20Extraction-8E44AD?style=for-the-badge)
![Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-E74C3C?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

# 🎬 IMDb Movie Review Sentiment Analysis using Machine Learning

A Machine Learning project that classifies IMDb movie reviews as **Positive** or **Negative** using **Natural Language Processing (NLP)**, **TF-IDF Vectorization**, and **Logistic Regression**.

---

## 📌 Project Overview

This project performs sentiment analysis on the IMDb Movie Reviews dataset. It demonstrates a complete NLP pipeline, including text preprocessing, exploratory data analysis (EDA), feature extraction, model training, evaluation, and prediction.

The trained model can accurately predict whether a movie review expresses a **Positive** or **Negative** sentiment.

---

## ✨ Features

- 📂 Load and explore the IMDb dataset
- 📊 Perform Exploratory Data Analysis (EDA)
- 🧹 Clean and preprocess text data
- 🔤 Remove HTML tags, URLs, punctuation, numbers, and stopwords
- 📝 Convert text into numerical features using TF-IDF
- 🤖 Train a Logistic Regression classifier
- 📈 Evaluate the model using multiple performance metrics
- ☁️ Generate Positive and Negative Word Clouds
- 💾 Save the trained model and vectorizer
- 🎯 Predict sentiment for custom movie reviews

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud
- Joblib
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** IMDb Movie Reviews Dataset (50,000 Reviews)

- 25,000 Positive Reviews
- 25,000 Negative Reviews

The dataset contains labeled movie reviews for binary sentiment classification.

---

## ⚙️ Project Workflow

1. Import Libraries
2. Load Dataset
3. Perform Exploratory Data Analysis (EDA)
4. Clean and Preprocess Text
5. Remove Stopwords
6. Convert Text using TF-IDF
7. Split Dataset into Training and Testing Sets
8. Train Logistic Regression Model
9. Evaluate Model Performance
10. Save Model and Vectorizer
11. Predict Custom Reviews

---

## 📊 Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## 📁 Project Structure

```
IMDb-Movie-Review-Sentiment-Analysis/
│
├── Task_3_Sentiment_Analysis.ipynb
├── IMDB Dataset.csv
├── sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── images/
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/IMDb-Movie-Review-Sentiment-Analysis.git
```

Move into the project folder:

```bash
cd IMDb-Movie-Review-Sentiment-Analysis
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Task_3_Sentiment_Analysis.ipynb
```

---

## 🎯 Future Improvements

- Deep Learning (LSTM/Bi-LSTM)
- Transformer Models (BERT)
- Streamlit Web Application
- Flask API Deployment
- Multi-class Sentiment Classification

---

## 👨‍💻 Author

**Yash Kumar**

B.Tech Computer Science Engineering

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
