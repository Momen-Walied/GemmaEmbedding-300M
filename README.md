# 📚 Scientific Papers Embedding with SentenceTransformers (GemmaEmbedding)

This repository contains a high-level Jupyter Notebook that demonstrates how to:

- Load and process scientific papers (PDFs).  
- Chunk text into manageable sections.  
- Generate embeddings using the **latest GemmaEmbedding model** with [SentenceTransformers](https://www.sbert.net/).  
- Build a **FAISS vector store** for efficient retrieval.  
- Run simple search queries against the indexed paper chunks.  

---

## 🚀 Features
- **PDF ingestion & text chunking**  
- **State-of-the-art embeddings** (GemmaEmbedding)  
- **FAISS-based similarity search**  
- Easy to extend for **RAG (Retrieval-Augmented Generation)**  

---

## 🛠️ Installation

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

pip install -r requirements.txt
