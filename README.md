# DocuMind_AI
DocuMind AI – RAG Based SOP Assistant
# 📄 DocuMind – RAG Based SOP Assistant

DocuMind is an AI-powered document assistant that allows users to ask questions from company SOPs, HR policies, and internal documents.

The system uses Retrieval-Augmented Generation (RAG) to search relevant document chunks and generate accurate answers using a Large Language Model.

---

## 🚀 Features

- Ask questions from PDF documents
- Semantic search using vector embeddings
- AI-generated answers
- Chat interface using Streamlit
- Works with local open-source models

---

## 🧠 Tech Stack

Backend:
- Python

AI Framework:
- LangChain

Vector Database:
- FAISS

Embedding Model:
- sentence-transformers/all-MiniLM-L6-v2

LLM:
- Llama3 (via Ollama)

Frontend:
- Streamlit

---

## 📂 Project Structure

DocuMind-RAG

app.py – Streamlit UI  
ingest.py – document ingestion pipeline  
rag.py – RAG query engine  

documents/ – input PDFs  
vectorstore/ – FAISS database  

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/documind-rag
cd documind-rag
