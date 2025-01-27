# RAG-Indian-Constitution

## Overview
This project implements a **Retrieval-Augmented Generation (RAG)** model to create a **Question-Answering (QA) bot** for the Indian Constitution. The bot uses document retrieval and generative models to provide detailed and context-aware answers to user queries.

---

## Features
- **PDF Loader**: Efficiently loads and processes large PDF documents.
- **Text Splitting**: Splits documents into smaller, overlapping chunks for better indexing.
- **Vector Search**: Uses **FAISS** for similarity-based retrieval of relevant document chunks.
- **Generative Model**: Provides detailed answers using Hugging Face's transformer models like **Flan-T5**.
- **Customizable**: Parameters like chunk size, overlap, and retrieval models can be easily adjusted.

---

## Prerequisites
Ensure you have **Python 3.8+** installed. Install the required dependencies using:
```bash
pip install langchain huggingface_hub sentence-transformers faiss-cpu pypdf transformers accelerate bitsandbytes
