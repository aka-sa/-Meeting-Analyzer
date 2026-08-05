# 📚 Meeting Analyzer: Scalable Audio Intelligence System

An AI-powered Retrieval-Augmented Generation (RAG) assistant for answering questions from Distributed Database Management System (DDBMS) PDFs and images.

## 🚀 Features

- 📄 Upload PDF documents
- 🖼️ Upload images
- 🤖 Multimodal question answering using Qwen2.5-VL
- 🔍 Semantic search with FAISS
- 🧠 LangGraph-based RAG pipeline
- ⚡ FastAPI backend with streaming responses
- 📚 Source citations

## 🛠️ Tech Stack

- Python
- FastAPI
- LangGraph
- FAISS
- Hugging Face Transformers
- PyMuPDF
- HTML
- LLM



## 🔄 Workflow

```
Upload PDF/Image
       │
       ▼
Extract Text
       │
       ▼
Chunk Document
       │
       ▼
Generate Embeddings
       │
       ▼
FAISS Vector Store
       │
       ▼
Retrieve Relevant Chunks
       │
       ▼
      LLm
       │
       ▼
Generate Answer
```

## 💬 Example Questions

- What is a Distributed Database System?
- Explain Fragmentation.
- What is Two-Phase Commit?
- Explain Deadlock with an example.
- Compare Horizontal and Vertical Fragmentation.

## ▶️ Run Locally
-Youtube:[Youtube](https://youtu.be/ZKT6jCKoFgc)

## 📌 Future Improvements

- Hybrid Search
- GraphRAG
- Voice Assistant
- Mobile App
- PostgreSQL + pgvector
- Multi-user Authentication

## 📄 License

MIT License
