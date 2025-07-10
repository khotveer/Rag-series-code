# 🧠 RAG Series – Code Repository

This repository contains session-wise code for building a domain-specific Question Answering system using the **Retrieval-Augmented Generation (RAG)** framework.

We use **Quantum Computing notes** as the knowledge base and walk through each component in the RAG pipeline using practical, easy-to-follow notebooks.

---

## 📂 Repository Structure

### 📘 Notebooks

| Filename | Description |
|----------|-------------|
| `01. Embedding model.ipynb` | Introduction to RAG & Embedding generation using Sentence Transformers |
| `02.1. Data Prep.ipynb` | Preparing and formatting knowledge base (quantum notes) |
| `02.2-Vector_database_and_similarity_search.ipynb` | Creating vector store, performing similarity search |
| `02.2-Vector_database_and_similarity_search-Copy1.ipynb` | (Backup/variation of 02.2) |
| `02.3-Vector_database_reusing.ipynb` | How to load and reuse pre-built vector database |
| 🔗 **[Full Project Code Repository](https://github.com/khotveer/rag-embedding-pipeline)** | Complete RAG implementation from end to end |

### 📁 Folders

- `data/` → Contains input text data (quantum notes)
- `chroma_bge_768/` → Local ChromaDB vector store built using BGE-768 embedding model

---

## 📌 Tech Stack

- **Python**
- **Sentence Transformers** (`bge-small-en-v1.5`)
- **ChromaDB** for vector storage
- **Hugging Face Transformers**
- **LangChain** (optional integration)

---

## 🔗 Resources

- 🎥 [YouTube Playlist – RAG Series](https://www.youtube.com/playlist?list=PLvz-QS4T63WZycSpgi6K2bsMiAUgXkJP0)
- 💻 [GitHub – Full Project Repo](https://github.com/khotveer/rag-embedding-pipeline)
- 👨‍💼 [Connect on LinkedIn](https://www.linkedin.com/in/veer-khot-93177bab/)

---
