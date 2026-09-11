# 🤖 RAG Assistant Project

An end-to-end Retrieval-Augmented Generation (RAG) system built to query and interact with custom documents efficiently using LLMs and Vector Search.

---

## 🛠️ Tech Stack

- **Backend:** Python, FastAPI, LangChain / LlamaIndex
- **Vector Database:** ChromaDB
- **Frontend:** Next.js / React (or Streamlit)
- **Embeddings & LLM:** OpenAI / HuggingFace Models

---

## 📂 Project Structure

```text
rag-assistant-project/
│
├── backend/                # FastAPI backend & RAG logic
│   ├── data/               # Document storage & ChromaDB
│   ├── app.py              # API Endpoints
│   └── requirements.txt    # Python Dependencies
│
├── frontend/               # User interface code
├── .gitignore              # Ignored files (secrets & caches)
└── README.md               # Project documentation
