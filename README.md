# Retrieval Augmented Generation (RAG) for PDF Based Question Answering

This project demonstrates how to process PDF documents, split the text into smaller chunks, store the chunks in a vector database (Chroma), and perform Question-Answering (QA) tasks using Hugging Face models.

## Features
- Load PDF documents from a directory
- Split documents into smaller chunks for efficient processing
- Store the text chunks in a vector store (Chroma)
- Perform similarity search based on a query
- Generate answers using language models from Hugging Face
- Save and persist the processed data in Chroma for future use

## Requirements

- Python 3.x
- Langchain
- Hugging Face
- Chroma
- OpenAI API
- Sentence Transformers

## Installation

Clone this repository and install the required dependencies:

```bash
pip install langchain langchain_community pypdf chromadb langchain_huggingface openai tiktoken huggingface_hub
pip install sentence-transformers
