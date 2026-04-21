# 📊 Financial Sentiment Analysis using BERT and FinBERT

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?logo=huggingface&logoColor=black)
![NLP](https://img.shields.io/badge/NLP-6A5ACD)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

A comparative **Natural Language Processing (NLP)** project analyzing **financial sentiment**
using transformer-based models, focusing on **BERT vs FinBERT** and the impact of
**domain-specific pretraining**.

---

## 📌 Overview

This project performs **financial sentiment classification** by fine-tuning transformer models
to classify text into **positive, neutral, and negative sentiment**.

It compares **general-purpose BERT** with **domain-specific FinBERT** to evaluate how
financial-domain pretraining improves performance.

---

## 🚀 Features

- Sentiment classification using transformer models  
- Comparison between BERT and FinBERT  
- Data preprocessing and tokenization pipeline  
- Performance evaluation using standard metrics  

---

## 🧠 Models Used

### 🔹 BERT
- Model: `bert-base-uncased`  
- Pretrained on general-domain corpora  
- Used as baseline model  

### 🔹 FinBERT
- Model: `ProsusAI/finbert`  
- Pretrained on financial text  
- Designed for domain-specific sentiment understanding  

---

## 📂 Dataset

- Financial PhraseBank-style data  
- FiQA-style financial data  
- Labels: positive, neutral, negative  

All datasets were cleaned, normalized, and label-mapped consistently.

---

## ⚙️ Technologies Used

- Python  
- PyTorch  
- Hugging Face Transformers  
- Scikit-learn  
- Pandas, NumPy  

---

## 📈 Results Summary

- FinBERT outperformed BERT  
- Higher Accuracy and Macro-F1 score  
- Better understanding of financial context  

### 💡 Key Insight  
Domain-specific pretraining significantly improves sentiment classification performance.

---

## 📊 Evaluation Metrics

- Accuracy  
- Macro-F1 Score  
- Confusion Matrix Analysis  

---

## 🚀 Run on Google Colab

If the notebook does not render properly on GitHub, you can run it here:

👉 https://colab.research.google.com/github/Saji-d/financial-sentiment-analysis-bert/blob/main/financial_sentiment_bert_vs_finbert.ipynb

---

## 📄 Documentation

A detailed project report is included:

📘 `financial_sentiment_bert_vs_finbert.pdf`

---

## 🎓 Academic Context

This project was completed as part of Natural Language Processing coursework, focusing on:

- Transformer-based sentiment analysis  
- Fair experimental comparison  
- Financial-domain NLP modeling  
- Research-based evaluation  

---

## 📎 Note

This project is part of a larger natural language processing repository:  
👉 https://github.com/Saji-d/natural-language-processing  

---

## 👤 Author

**Sajidur Rahman Sajid**  
Computer Science & Engineering (CSE)  
Aspiring Machine Learning / NLP Engineer
