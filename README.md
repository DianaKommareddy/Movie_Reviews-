# Movie_Reviews
_**IMDB Sentiment Analysis with GloVe + LSTM**_

This project implements a sentiment analysis model on the IMDB movie reviews dataset using deep learning with pre-trained GloVe embeddings and a Bidirectional LSTM network. It classifies movie reviews as positive or negative.

## 🧠 Overview

1. Dataset: [IMDB Dataset]
2. Model: Embedding Layer (GloVe) + BiLSTM + Dense Layers
3. Embedding: GloVe 100d
4. Output: Binary classification (positive or negative sentiment)
5. Metrics: Accuracy, Confusion Matrix, and Classification Report

## 🚀 Features

- Uses GloVe word embeddings for semantic understanding
- Handles out-of-vocabulary (OOV) tokens
- Bidirectional LSTM layers to capture context from both directions
- Training visualization and evaluation with accuracy plots and heatmaps

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 📁 Dataset

You will need to download the IMDB dataset CSV :

- IMDB Dataset.csv: [Available here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)


## 📊 Results

- Achieved competitive accuracy on the test set.
- Outputs include confusion matrix and classification report.
- Accuracy curve over epochs for visual analysis.

## 📦 How to Run

1. Open the notebook in Google Colab.
2. Upload the following files:
   - IMDB Dataset.csv
   - glove.6B.100d.txt
3. Run all cells sequentially.

## 📈 Output Visuals

- Confusion Matrix
- Accuracy over Epochs
- Precision, Recall, and F1-Score

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).


---
