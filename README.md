# 📊 Financial Sentiment Analysis using BERT and FinBERT

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?logo=huggingface&logoColor=black)
![NLP](https://img.shields.io/badge/NLP-6A5ACD)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

A comparative **Natural Language Processing (NLP)** project analyzing **financial sentiment**
using transformer-based models, with a focus on **BERT vs FinBERT** and the impact of
**domain-specific pretraining**.

---

## 📌 Overview

This project presents a **comparative study of BERT and FinBERT** for **financial sentiment classification**.  
The task involves classifying financial text into **positive, neutral, and negative sentiment**
using transformer models fine-tuned under identical experimental conditions.

The goal is to evaluate how **domain-adapted language models** perform compared to
general-purpose transformers on financial text.

---

## 🎯 Objectives

- Perform sentiment analysis on financial text data  
- Compare **general-purpose BERT** with **domain-specific FinBERT**  
- Evaluate model performance using standard classification metrics  
- Analyze the effect of financial-domain pretraining  

---

## 🧠 Models Used

### 🔹 BERT
- Model: `bert-base-uncased`  
- Pretrained on general-domain corpora  
- Used as a baseline transformer model  

### 🔹 FinBERT
- Model: `ProsusAI/finbert`  
- Pretrained on financial news and reports  
- Designed to capture domain-specific financial sentiment  

---

## 📂 Datasets

Experiments were conducted using **public financial sentiment datasets**, including:

- **Financial PhraseBank–style data**
  - Financial news headlines and short statements  
  - Labels: positive, neutral, negative  

- **FiQA-style financial data**
  - Financial questions, reports, and market-related text  
  - Labels: positive, neutral, negative  

All datasets were **cleaned, normalized, and label-mapped consistently** prior to training.

---

## ⚙️ Experimental Setup

- Language: Python 3  
- Framework: PyTorch  
- Libraries: Hugging Face Transformers, Scikit-learn, NumPy, Pandas, Matplotlib  
- Platform: GPU-enabled environment (Google Colab)  

### Training Configuration

- Epochs: 3  
- Learning Rate: 2e-5  
- Batch Size: 16  
- Max Sequence Length: 128  
- Optimizer: AdamW  
- Loss Function: Cross Entropy  

---

## 📈 Results Summary

- **FinBERT consistently outperformed BERT**  
- Higher **Accuracy** and **Macro-F1 score**  
- Reduced confusion between neutral and positive classes  
- Stronger understanding of financial-domain context  

### 💡 Key Insight

Domain-specific pretraining significantly improves sentiment classification performance
for financial text.

---

## 📊 Evaluation Metrics

- Accuracy  
- Macro-F1 Score  
- Confusion Matrix Analysis  

---

## 📄 Documentation

A detailed project report is included, covering:

- Dataset description  
- Model architecture  
- Training methodology  
- Experimental results  
- Confusion matrix analysis  

📘 **Report:**  
`financial_sentiment_bert_vs_finbert.pdf`

---

## 🎓 Academic Context

This project was completed as part of **Natural Language Processing coursework**, with emphasis on:

- Transformer-based sentiment analysis  
- Fair experimental comparison  
- Financial-domain NLP modeling  
- Research-oriented evaluation and reporting  

---

## 📎 Note

This project is part of a larger natural language processing repository:  
👉 https://github.com/Saji-d/natural-language-processing-projects  

---

## 👤 Author

**Sajidur Rahman Sajid**  
Computer Science & Engineering (CSE)  
Aspiring Machine Learning / NLP Engineer
