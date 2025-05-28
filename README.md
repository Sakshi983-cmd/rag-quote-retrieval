# rag-quote-retrieval
# 🧠 RAG-Based Quote Retrieval App

This project is a semantic quote finder using Retrieval-Augmented Generation (RAG) with the `Abirate/english_quotes` dataset.

## ✨ Features

- Semantic search using `sentence-transformers`
- Quote retrieval using FAISS
- Answer generation using open-source LLM (`Mistral`)
- Streamlit web interface

## 🚀 How to Run

### Local
```bash
pip install -r requirements.txt
streamlit run rag_quotes_app.py
