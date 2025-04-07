# 📝 NLP Text Classification with Logistic Regression & Naive Bayes

## 📚 Course Information

- **Course Name:** Deep Learning  
- **Lab Title:** NLP Techniques for Text Classification
- 
---

## 🎯 Objective

To implement and compare NLP-based text classification techniques using Logistic Regression and Naive Bayes. The assignment focuses on preprocessing textual data, transforming it into numerical form, and evaluating model performance.

---

## 📖 Brief Theory

### 🔹 Natural Language Processing (NLP)
NLP enables machines to understand and interpret human language. It involves techniques like:
- **Tokenization** – Breaking text into words or tokens.
- **Stopword Removal** – Filtering out common words like "the", "and", etc.
- **Stemming** – Reducing words to their root form (e.g., “playing” → “play”).
- **Lemmatization** – More accurate word reduction using linguistic knowledge.

### 🔹 Text Vectorization
Machines can't understand raw text, so we convert it into numerical vectors using:
- **CountVectorizer** – Counts word frequency in a document.
- **TF-IDF (Term Frequency-Inverse Document Frequency)** – Considers how important a word is across documents.

### 🔹 Classification Algorithms
- **Logistic Regression** – A linear model used for binary or multiclass classification.
- **Multinomial Naive Bayes** – A probabilistic model based on Bayes' Theorem, good for text data.

---

## 🗂 Dataset

- **Dataset Used:** AG News Dataset  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset)  
- **Classes:** 4 (World, Sports, Business, Sci/Tech)  
- **Attributes:** Title, Description, Label (Class)  

---

## ⚙️ Project Structure

```bash
├── ag_news/
│   ├── train.csv
│   └── test.csv
├── NLP_Text_Classification_SanikaKundekar.ipynb
├── README.md
└── Output Screenshots/

---
## 🧠 Models Implemented

### 1. Logistic Regression
- Works well for linearly separable data.
- Used with TF-IDF features.
- **Accuracy:** 88.62% | **F1 Score:** 0.8862

### 2. Naive Bayes
- Fast and efficient for large text data.
- Used with CountVectorizer and smoothing `alpha=0.52`.
- **Accuracy:** 88.42% | **F1 Score:** 0.8842

---

## 📊 Results Summary

| Model               | Accuracy | F1 Score |
|--------------------|----------|----------|
| Logistic Regression| 88.62%   | 0.8862   |
| Naive Bayes        | 88.42%   | 0.8842   |

- Visual comparisons include bar graphs and confusion matrices.

---

## 🧪 Evaluation Metrics

- **Accuracy** – Percentage of correct predictions.
- **F1 Score** – Harmonic mean of precision and recall.
- **Classification Report** – Shows precision, recall, and F1 per class.
- **Confusion Matrix** – Displays true vs predicted labels.

---

## 📌 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the `ag_news` folder containing `train.csv` and `test.csv`.
3. Run all cells from top to bottom.
4. View the model performance metrics and graphs at the end.

---

## 📷 Screenshots

| Confusion Matrix - Logistic Regression | Confusion Matrix - Naive Bayes |
|---------------------------------------|--------------------------------|
| ![Logistic CM](path/to/logistic_cm.png) | ![NaiveBayes CM](path/to/nb_cm.png) |

| Accuracy vs F1 Score |
|----------------------|
| ![Model Comparison](path/to/comparison_chart.png) |

---

## 📌 Declaration

> I, Sanika Kundekar, confirm that the work submitted in this assignment is my own and has been completed following academic integrity guidelines.

---

## 🔗 GitHub Repository

👉 [GitHub Repo Link](https://github.com/yourusername/NLP-Text-Classification)
