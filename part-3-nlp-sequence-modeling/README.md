# Customer Support Sentiment Classification using NLP

## Project Overview

This project implements a Natural Language Processing (NLP) pipeline for customer support sentiment classification.

The objective is to classify customer support messages into:
- Positive
- Neutral
- Negative

The project demonstrates text preprocessing, TF-IDF vectorization, machine learning classification, and sentiment prediction using Python and Scikit-learn.

---

## Dataset Information

The dataset contains customer support messages along with sentiment labels.

### Dataset Features
- ticket_id
- channel
- customer_message
- sentiment_label
- word_count
- urgent_flag

### Sentiment Classes
- Positive
- Neutral
- Negative

Dataset Size: 1500 records

---

## Project Workflow

### 1. Data Exploration
- Dataset inspection
- Sentiment distribution analysis
- Text length analysis

### 2. Text Preprocessing
- Lowercase conversion
- Removal of punctuation
- Tokenization
- Stopword removal

### 3. Text Vectorization
- TF-IDF vectorization
- Feature extraction from text

### 4. Model Training
Baseline Machine Learning Model:
- Logistic Regression

### 5. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
- Sample Predictions

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- NLTK

---

## Results

The Logistic Regression baseline model achieved excellent sentiment classification performance with highly accurate predictions across all sentiment classes.

The confusion matrix demonstrated strong classification capability with minimal prediction errors.

---

## Folder Structure

```text
part-3-nlp-sequence-modeling/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── customer_support_text_classification.csv
│
├── results/
│   └── model_evaluation.png
│
├── sample_predictions/
│   └── sample_predictions.txt
```

---

## Future Improvements

- Implement LSTM and GRU sequence models
- Use pretrained word embeddings
- Apply Transformer-based architectures
- Deploy as a real-time sentiment analysis application

---

## Author

Ayush Mishra