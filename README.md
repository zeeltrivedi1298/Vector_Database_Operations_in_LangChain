
# Vector Database Operations in LangChain

This project demonstrates how to use **LangChain** with a **Vector Database (Chroma)** to build the foundation for Retrieval-Augmented Generation (RAG) applications.  

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
