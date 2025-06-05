# IMDB Sentiment Analysis using Naive Bayes

This project uses the IMDB movie reviews dataset to perform sentiment analysis (positive/negative classification) using a Naive Bayes algorithm.

## 📘 Project Overview

- **Goal**: Classify IMDB reviews as either positive or negative.
- **Model Used**: Naive Bayes (MultinomialNB)
- **Dataset**: IMDB reviews dataset (text + labels)
- **Notebook**: `IMDB+BayesAlgorithm.ipynb`

## 🔧 Features

- Data preprocessing and text cleaning (stopword removal, tokenization)
- TF-IDF vectorization for text features
- Naive Bayes model training
- Accuracy, confusion matrix, and evaluation metrics

## 🛠️ Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
```

### Sample `requirements.txt`:
```
numpy
pandas
scikit-learn
nltk
matplotlib
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/imdb-naive-bayes.git
   cd imdb-naive-bayes
   ```

2. Open the notebook:
   ```bash
   jupyter notebook IMDB+BayesAlgorithm.ipynb
   ```

3. Run the cells sequentially to train and test the model.

## 📊 Results

- Model Accuracy: ~85% (depending on dataset split and preprocessing)
- Confusion Matrix and classification report included in notebook

## 📁 Files

- `IMDB+BayesAlgorithm.ipynb` — Main Jupyter Notebook
- `README.md` — Project documentation
- `requirements.txt` — Python dependencies

## 🧠 Concepts Used

- Natural Language Processing (NLP)
- Machine Learning
- Naive Bayes Classification
- TF-IDF Vectorization

## 📌 License

MIT License
