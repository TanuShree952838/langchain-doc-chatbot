# LangChain Document Chatbot

Chat with your own documents using LangChain, FAISS, Hugging Face models, and sentence-transformer embeddings.

## Features

- Load `.pdf` or `.txt` files
- Split documents into chunks
- Embed using `all-MiniLM-L6-v2` from HuggingFace
- Store & search embeddings using FAISS
- Query the document using `GPT2` from HuggingFace

## Installation

```bash
pip install -r requirements.txt
