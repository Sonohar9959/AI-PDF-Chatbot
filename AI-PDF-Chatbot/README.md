# AI PDF Chatbot

A simple AI chatbot that answers questions from uploaded PDF documents using Retrieval-Augmented Generation (RAG).

## Features

- Upload PDF documents
- Extract text from PDFs
- Split text into smaller chunks
- Create embeddings for semantic search
- Retrieve relevant PDF content based on user questions
- Generate answers using an LLM
- Simple chat interface

## Tech Stack

- Python
- LangChain
- OpenAI / LLM
- FAISS / Vector Database
- PDF Parser
- Streamlit

## How It Works

1. User uploads a PDF file.
2. Text is extracted from the PDF.
3. Extracted text is split into chunks.
4. Embeddings are created and stored in a vector database.
5. User asks a question.
6. Relevant chunks are retrieved.
7. LLM generates an answer using the retrieved content.

## Setup

```bash
pip install -r requirements.txt