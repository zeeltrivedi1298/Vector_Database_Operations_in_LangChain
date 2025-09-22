
# Vector Database Operations in LangChain

This project demonstrates how to use **LangChain** with a **Vector Database (Chroma)** to build intelligent document search and retrieval systems.  

## 🚀 Features
- Install and configure LangChain + Chroma
- Ingest documents (PDF/Text) and create embeddings
- Store and manage vectors in Chroma
- Query data using LangChain retrievers
- End-to-end example of building a retrieval pipeline

## 🔑 Business Relevance
Credit card fraud, customer support automation, and search personalization rely on **fast, accurate retrieval of context**.  
This notebook shows how vector databases + LangChain can **solve real-world problems** by enabling contextual AI.

**Result → 0 (Legit) or 1 (Fraud)**  
*(Example: how RAG + embeddings can detect fraud patterns by comparing transaction vectors)*

## 📦 Installation
```bash
pip install langchain langchain-openai langchain-community
pip install langchain-chroma pymupdf jq

▶️ Usage

Enter your OpenAI API key in the notebook.

Run cells step by step:

Setup ChromaDB
Embed documents
Store & retrieve vectors
Query with LangChain retriever
Experiment with your own PDFs or text data.

📂 File

Vector_Database_Operations_in_LangChain_WithZeel.ipynb

🧠 Learnings

Basics of vector embeddings
How Chroma stores and queries vectors
How LangChain integrates retrieval into AI workflows
