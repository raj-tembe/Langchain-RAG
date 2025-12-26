# Langchain-RAG 🚀

> A hands-on exploration of **Retrieval-Augmented Generation (RAG)** using **LangChain** — includes simple and advanced RAG workflows in Jupyter notebooks.

This repository was created as part of learning and experimenting with **RAG architectures** using LangChain 🦜🔗. Expect notebooks demonstrating how to build RAG pipelines from scratch to more advanced variants.  
(⚠️ Note: this is a learning repository — there may be rough edges or beginner-level code.)

---

## 📌 What Is RAG?

**Retrieval-Augmented Generation (RAG)** is a technique that improves the factual accuracy and relevance of large language model outputs by retrieving external documents and using them as context in generation. Instead of relying on the model’s fixed pretrained knowledge, RAG augments the model with dynamic, external content. :contentReference[oaicite:0]{index=0}

---

## 🗂 Repository Contents

| File | Description |
|------|-------------|
| `SimpleRAG.ipynb` | Introductory RAG example — basic document ingestion, vector store creation, and QA with LangChain. |
| `ADV-RAG-PIPELINE.ipynb` | More advanced RAG pipeline with enhanced retrieval, text splitting, embeddings & optimized workflow. |
| `.gitignore` | Standard Python/git ignore patterns. |
| `LICENSE` | MIT License. |
| `README.md` | This documentation. |

---

## 🚀 Getting Started

These notebooks are designed to be run in a Jupyter environment.

### 1. Clone the Repo

```bash
git clone https://github.com/raj-tembe/Langchain-RAG.git
cd Langchain-RAG
