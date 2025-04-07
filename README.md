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
