# RAGifyyy

RAGifyyy is a Python project for **retrieval-augmented generation (RAG)** using PDFs and text data.  
It allows you to load documents, create embeddings, and query them using a language model.

---

## Features

- Load PDFs and text files into the project.
- Create vector embeddings for documents.
- Perform semantic search and question answering.
- Supports large files with Git LFS.
- Compatible with Jupyter Notebook (`.ipynb`) and Python scripts.

---



## Project Structure

rag_clean/ # Root folder
├─ notebook/ # Jupyter notebooks
│ ├─ document.ipynb
│ └─ pdf_loader.ipynb
├─ data/
│ ├─ pdf/ # PDFs used in the project
│ ├─ text_files/ # Additional text documents
│ └─ vector_store/ # Embeddings and vector database
├─ main.py # Main Python script
├─ requirements.txt # Python dependencies
├─ pyproject.toml # Project config
└─ .gitignore # Git ignore file
