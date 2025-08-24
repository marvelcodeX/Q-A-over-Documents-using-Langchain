# Q&A over Documents using Langchain

This is a **document question-answering system** built with [LangChain](https://python.langchain.com/), [FAISS](https://faiss.ai/), and [Hugging Face Transformers](https://huggingface.co/).  
It allows you to **upload a document (PDF, DOCX, or TXT)**, automatically process it into embeddings, and ask natural language questions to get contextual answers.

---

## 🚀 Features
- Upload documents in **PDF, Word (.docx), or plain text (.txt)** format.
- **Automatic text chunking** for efficient retrieval.
- Uses **FAISS** for fast similarity search.
- Embeddings from **sentence-transformers/all-MiniLM-L6-v2**.
- Powered by **FLAN-T5-large** for answer generation.
- Interactive **Q&A loop** where you can query until you type `exit`.

---

## 📦 Installation

Install dependencies:

```bash
pip install langchain langchain-community faiss-cpu pypdf python-docx sentence-transformers transformers
