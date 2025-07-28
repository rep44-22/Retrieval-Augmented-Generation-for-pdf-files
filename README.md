# 📄 Retrieval-Augmented Generation (RAG) on PDF using FAISS & OpenAI

This project implements a **Retrieval-Augmented Generation (RAG)** system that allows users to ask natural language questions about the contents of a PDF. It uses **OpenAI's embedding and chat models**, and **FAISS** for efficient semantic search over the document.

---

## 🚀 Features

- 📄 Extracts text from PDF files using PyPDF2
- ✂️ Splits the text into overlapping chunks
- 🧠 Generates embeddings using OpenAI
- 🧾 Stores and retrieves text chunks using FAISS for fast similarity search
- 💬 Answers questions using GPT-3.5 based on relevant context

---

## 🧰 Tech Stack

- Python 3.10+
- OpenAI API
- FAISS
- PyPDF2
- NumPy
- dotenv
- pickle

---

## 📁 Project Structure
├── main.py # Main script to run RAG over PDF
├── hp_azkaban.pdf # Input PDF file
├── faiss_index.bin # Saved FAISS index
├── embeddings.pkl # Pickled embeddings
├── documents.pkl # Pickled text chunks
├── .env # Contains your OpenAI API key
└── README.md
