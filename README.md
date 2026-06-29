# 🎬 Movie Review Sentiment Analysis using ANN & LSTM

A Deep Learning based Natural Language Processing (NLP) project that classifies IMDB movie reviews into **Positive** or **Negative** sentiments using two different neural network architectures: **Feed Forward Artificial Neural Network (ANN)** and **Long Short-Term Memory (LSTM)**.

The project compares the performance of both models and demonstrates the effectiveness of sequence-based learning for sentiment classification.

---

## 📌 Features

- Movie Review Sentiment Analysis
- Binary Classification (Positive / Negative)
- Text Preprocessing Pipeline
- Stopword Removal
- HTML Tag Removal
- Lemmatization
- TF-IDF Vectorization (ANN)
- Tokenization & Padding (LSTM)
- Feed Forward ANN Model
- LSTM Deep Learning Model
- Confusion Matrix
- Classification Report
- Model Performance Comparison

---

## 📂 Dataset

Dataset used in this project:

IMDB Movie Reviews Dataset

https://www.kaggle.com/datasets/vishakhdapat/imdb-movie-reviews

Dataset contains:

- 50,000 Movie Reviews
- Positive Reviews
- Negative Reviews
- Balanced Dataset

---

## 🧠 Models Used

### Feed Forward Artificial Neural Network (ANN)

- TF-IDF Vectorization
- Dense Layer
- Dropout
- Binary Classification

### Long Short-Term Memory (LSTM)

- Tokenizer
- Padding
- Embedding Layer
- LSTM Layer
- Dense Layer
- Sigmoid Output

---

## ⚙️ Text Preprocessing

The following preprocessing steps are applied:

- Remove HTML Tags
- Remove Punctuation
- Remove Numbers
- Convert Text to Lowercase
- Remove Stopwords
- Lemmatization
- Tokenization
- Sequence Padding

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK

---

## 📁 Project Structure

```
Movie_Review_Sentiment_Analysis/
│
├── IMDB Dataset.csv
├── Movie_Review_ANN.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/HanumeshGupta/Movie_Review_Sentiment_Analysis.git
```

Move into the project directory

```bash
cd Movie_Review_Sentiment_Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📈 Workflow

```
Dataset
      │
      ▼
Text Cleaning
      │
      ▼
Stopword Removal
      │
      ▼
Lemmatization
      │
      ▼
Train/Test Split
      │
      ├───────────────┐
      ▼               ▼
   TF-IDF         Tokenizer
      │               │
      ▼               ▼
     ANN            LSTM
      │               │
      └───────┬───────┘
              ▼
     Model Evaluation
              ▼
      Performance Comparison
```

---

## 📌 Future Improvements

- Streamlit Web Application
- Hyperparameter Tuning
- GRU Model
- Bidirectional LSTM
- Transformer-based Models (BERT)
- Model Deployment

---

