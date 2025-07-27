# 📚 RAG  Q&A Chatbot 🤖

This is a Retrieval-Augmented Generation (RAG) based chatbot that lets you **upload a PDF** and **ask questions** about its contents using **LangChain**, **Hugging Face Transformers**, and **Gradio**.

---

## 🚀 Features

- ✅ Upload any PDF file (books, research papers, notes)
- 🔍 Extracts content and chunks it for retrieval
- 🧠 Uses `sentence-transformers` for embeddings
- 🤖 Generates intelligent answers using `Falcon-RW-1B` via Hugging Face
- 💬 Chat interface powered by Gradio

---

## 🛠️ Built With

- [LangChain](https://python.langchain.com/)
- [Gradio](https://gradio.app/)
- [Transformers](https://huggingface.co/transformers/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Sentence Transformers](https://www.sbert.net/)
- [Falcon-RW-1B Model](https://huggingface.co/tiiuae/falcon-rw-1b)

---

## 📦 How It Works

1. Upload a `.pdf` file
2. The file is parsed and chunked
3. Each chunk is converted to a vector using Sentence Transformers
4. The user's query is compared against the chunks using FAISS
5. The most relevant context is passed to Falcon-RW-1B to generate an answer

---



