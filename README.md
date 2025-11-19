# SMS Spam Classification — NLP-I Course Project

## Overview

This project applies NLP and machine learning methods to classify SMS messages as 'spam' or 'ham'.

- **Dataset:** SMS Spam Collection (UCI ML Repository)
- **Objective:** Achieve robust spam detection using thorough preprocessing, analysis, and ML model comparison.

---

## Workflow and How It Supports Grading Requirements

| Task         | How This Project Covers the Grading Criteria |
|--------------|----------------------------------------------|
| **Data**     | Real SMS data loaded, EDA (class counts, imbalance, sample texts, plots) for deep understanding |
| **Preprocess** | Complete cleaning (lowercase, punctuation removal, stopwords, tokenization), TF-IDF vectorization, train/test split — all steps shown and explained |
| **Model**    | Trained & compared three models: Naive Bayes, Logistic Regression, Random Forest |
| **Evaluate** | Classified and evaluated with accuracy, recall, precision, F1-score, confusion matrices. Benchmarking: compared and discussed model performance |
| **Application** | Function `predict_spam(message)` for easy demo/deployment, showing pipeline. All technical terms used. |
| **Conclusion & Discussion** | Discussed model selection, limitations (imbalance, error cases), and future opportunities (e.g. neural networks, better features) |

---

## Steps

### 1. Data
- Loaded SMS Spam Collection data.
- Performed **EDA**: size, class imbalance, sample message inspection, visualization.

### 2. Preprocessing
- Text cleaned and tokenized (code + comments).
- Features engineered via **TF-IDF**.
- Train/test split visualized and explained.

### 3. Modeling
- Models trained:
  - **Naive Bayes**
  - **Logistic Regression**
  - **Random Forest**
- Training code and rationale for each model.

### 4. Evaluation
- Metrics: Accuracy, Recall, Precision, F1-score for each model.
- Confusion matrix visualizations for performance insight.
- **Model comparison**: Chose Random Forest; explicitly benchmarked others.

### 5. Application & Demo
- `predict_spam(message)` function for real-time demo.
- Usage examples included in notebook.
- Can convert to web/CLI app.

### 6. Conclusion & Reflection
- Explained why Random Forest performed best.
- Highlighted limitations (imbalance, feature scope).
- Cited opportunities (LSTM, BERT, resampling, app deployment).
- All workflow steps clearly annotated and mapped to grading criteria.

---

## How to Run

1. Download notebook and run in Google Colab/Jupyter.
2. Execute code cells in order.
3. Use `predict_spam("your message")` for spam prediction.

---

## Video Demo



---

## Requirements

- Python 3.x
- pandas, scikit-learn, nltk, matplotlib, seaborn

---

## Credits

- NLP-I, University of Debrecen
- Author: Vladimir Alrayyan

