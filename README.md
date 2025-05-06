# 🧠 RAG using LangChain

This repository contains a Jupyter Notebook that demonstrates how to build a simple Retrieval-Augmented Generation (RAG) pipeline using the [LangChain](https://www.langchain.com/) framework.

## 📌 Overview

Retrieval-Augmented Generation (RAG) enhances the response quality of language models by retrieving relevant context documents from a knowledge base. This notebook outlines the full pipeline, including:

- Document loading
- Chunking and embedding generation
- Vector storage using FAISS
- Retrieval of relevant documents
- Query answering using an LLM

## 📁 Files

- `rag_using_langchain.ipynb` — Main notebook that walks through the RAG implementation step by step.

## 🛠️ Setup Instructions

1. **Clone the repository** or download the notebook directly.

2. **Install required packages**:

```bash
pip install langchain faiss-cpu openai tiktoken python-dotenv
OPENAI_API_KEY=your-api-key
jupyter notebook rag_using_langchain.ipynb



📚 References
LangChain Documentation
FAISS GitHub
OpenAI API
Together API



