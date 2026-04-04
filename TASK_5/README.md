# 🚀 NLP Task 5 — Token Classification (POS Tagging & Chunking using BERT)

## 📌 Project Overview
This project implements a token classification system using BERT to perform POS Tagging and Chunking. The goal is to understand how transformer models process text at both word and phrase levels.

---

## ⚙️ Features
- Tokenization using BERT tokenizer
- Label alignment handling subwords
- Training using PyTorch
- Evaluation using Precision, Recall, F1 Score
- Inference on custom sentences

---

## 🧠 Concepts Covered
- Token Classification
- POS Tagging
- Chunking
- BERT Fine-Tuning
- Label Alignment
- Sequence Evaluation

---

## 📊 Model Performance
- Precision: 1.0  
- Recall: 0.22  
- F1 Score: 0.36  

> Note: Performance is limited due to small offline dataset.

---

## 🔍 Sample Inference
Input:
John works at Google in California  

Output:
('John', 'O'), ('works', 'O'), ('at', 'O'), ('Google', 'O'), ...

---

## ⚠️ Limitations
- Small dataset used (offline mode)
- Model predicts mostly "O" labels
- Performance improves with larger datasets

---

## 🚀 Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- SeqEval

---

## 📌 Conclusion
This project demonstrates how transformer models like BERT can be used for sequence labeling tasks. It highlights the importance of preprocessing and label alignment in NLP pipelines.

---

## 👨‍💻 Author
Varshith
