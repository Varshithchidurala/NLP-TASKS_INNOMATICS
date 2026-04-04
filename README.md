# 🧠 NLP Internship Tasks — Innomatics

This repository contains all my NLP assignments completed as part of my internship.  
It covers the full journey from basic preprocessing → ML models → Transformers → BERT fine-tuning.

---

# 📌 Tasks Overview

## 🔹 Task 1 — Text Preprocessing
Built a custom preprocessing pipeline to clean raw text data.

### Features:
- Lowercasing
- Removing numbers
- Removing URLs & emails
- Removing extra spaces
- Handling repeated characters
- Removing short tokens (≤2 except "no", "not")

### Output:
- Cleaned tokens
- Cleaned sentences

---

## 🔹 Task 2 — Sentiment Analysis (ML Models)
Built an end-to-end sentiment analysis pipeline.

### Steps:
- Data preprocessing
- Feature Engineering:
  - Bag of Words (BoW)
  - TF-IDF
- Models:
  - Logistic Regression
  - Naive Bayes
  - Decision Tree

### Evaluation:
- Accuracy
- Precision
- Recall
- F1 Score

### Insight:
Compared multiple models and identified best performing approach.

---

## 🔹 Task 3 — Chatbot using Transformers
Built a conversational chatbot using Hugging Face models.

### Features:
- Interactive chatbot (console-based)
- Uses pre-trained transformer model
- Continuous conversation loop
- Exit condition (exit / quit)

### Models Used:
- DialoGPT / GPT-based model

---

## 🔹 Task 4 — BERT Fine-Tuning (Sentiment Analysis)
Fine-tuned BERT for text classification.

### Steps:
- Dataset preprocessing
- Train / Validation / Test split
- Tokenization using BERT tokenizer
- Model:
  - AutoModelForSequenceClassification

### Experiments:
1. Frozen BERT (only classifier trained)
2. Fine-tuning last 2 layers

### Evaluation:
- Accuracy
- Precision
- Recall
- F1 Score

### Key Insight:
Fine-tuning improved performance significantly over frozen model.

---

## 🔹 Task 5 — Token Classification (POS Tagging & Chunking)
Built a token classification model using BERT.

### Features:
- Tokenization with label alignment
- Handling subwords and -100 labels
- Model:
  - AutoModelForTokenClassification
- Training using PyTorch

### Evaluation:
- Precision
- Recall
- F1 Score

### Inference:
Predict tags for custom sentences.

### Insight:
- POS tagging → word-level
- Chunking → phrase-level
- Label alignment is critical

---

# 🛠️ Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- SeqEval

---

# 📊 Key Learnings

- Importance of text preprocessing in NLP
- Difference between traditional ML and transformer models
- Understanding tokenization & subword handling
- Fine-tuning BERT for real-world tasks
- Sequence labeling challenges

---

# ⚠️ Limitations

- Some tasks use small datasets (offline setup)
- Model performance can improve with larger datasets

---

# 🚀 Future Improvements

- Use larger datasets
- Implement advanced models (RoBERTa, DistilBERT)
- Deploy models as APIs
- Build web-based chatbot interface

---

# 👨‍💻 Author

**Varshith**

---

# 🔗 Connect with Me

- LinkedIn: Varshith Chidurala
- GitHub: Varshithchidurala
