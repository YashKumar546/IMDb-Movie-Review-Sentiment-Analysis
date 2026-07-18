# 🎬 IMDb Movie Review Sentiment Analysis using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-2ECC71?style=for-the-badge)
![TF-IDF](https://img.shields.io/badge/TF--IDF-Feature%20Extraction-8E44AD?style=for-the-badge)
![Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-E74C3C?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A Machine Learning project that classifies IMDb movie reviews as **Positive** or **Negative** using **Natural Language Processing (NLP)**, **TF-IDF Vectorization**, and **Logistic Regression**.

---

## 📖 Project Overview

Sentiment Analysis is one of the most common Natural Language Processing (NLP) tasks. This project demonstrates an end-to-end machine learning workflow by classifying IMDb movie reviews into **Positive** or **Negative** sentiments.

The project covers every stage of a real-world NLP pipeline—from data preprocessing and exploratory data analysis (EDA) to feature extraction, model training, evaluation, and prediction.

---

## ✨ Features

- 📂 Load and explore the IMDb Movie Reviews dataset
- 📊 Perform Exploratory Data Analysis (EDA)
- 🧹 Clean and preprocess textual data
- 🔤 Remove HTML tags, URLs, punctuation, numbers, and stopwords
- 📝 Convert text into numerical features using TF-IDF
- 🤖 Train a Logistic Regression classifier
- 📈 Evaluate the model using multiple performance metrics
- ☁️ Generate Positive and Negative Word Clouds
- 💾 Save the trained model and vectorizer
- 🎯 Predict sentiment for custom movie reviews

---

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Natural Language Processing | NLTK |
| Feature Extraction | TF-IDF Vectorizer |
| Machine Learning | Scikit-learn |
| Model | Logistic Regression |
| Model Persistence | Joblib |
| Development Environment | Jupyter Notebook |

---

## 📂 Dataset

**Dataset:** IMDb Movie Reviews Dataset

- **Total Reviews:** 50,000
- **Positive Reviews:** 25,000
- **Negative Reviews:** 25,000

The dataset contains labeled movie reviews used for binary sentiment classification.

---

## ⚙️ Project Workflow

```text
Import Libraries
        │
        ▼
Load IMDb Dataset
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Text Cleaning & Preprocessing
        │
        ▼
Stopword Removal
        │
        ▼
TF-IDF Feature Extraction
        │
        ▼
Train-Test Split
        │
        ▼
Train Logistic Regression Model
        │
        ▼
Model Evaluation
        │
        ▼
Save Model & Vectorizer
        │
        ▼
Predict Custom Movie Reviews
```

---

## 📊 Model Evaluation

The model was evaluated using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1-Score
- ✅ Classification Report
- ✅ Confusion Matrix

---

## 📷 Project Screenshots

> Add screenshots of your notebook outputs here after uploading them to the `images/` folder.

Example:

```markdown
![Sentiment Distribution](images/sentiment_distribution.png)

![Confusion Matrix](images/confusion_matrix.png)

![Positive Word Cloud](images/positive_wordcloud.png)

![Negative Word Cloud](images/negative_wordcloud.png)
```

---

## 📁 Project Structure

```text
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

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/IMDb-Movie-Review-Sentiment-Analysis.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd IMDb-Movie-Review-Sentiment-Analysis
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Task_3_Sentiment_Analysis.ipynb
```

Run all cells to reproduce the complete workflow.

---

## 🔮 Future Improvements

- Deep Learning using LSTM/Bi-LSTM
- Transformer-based models (BERT)
- Streamlit Web Application
- Flask/FastAPI Deployment
- Multi-class Sentiment Analysis
- Hyperparameter Tuning

---

## 👨‍💻 Author

**Yash Kumar**

B.Tech Computer Science Engineering

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

If you find this project useful, feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub. It helps others discover the project and supports my work.
