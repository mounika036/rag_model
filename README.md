# RAG - Retrieval-Augmented Generation

A simple Retrieval-Augmented Generation (RAG) project that allows an LLM to answer questions using information retrieved from a PDF document.

## Features

* Loads and processes PDF documents using Docling.
* Splits documents into smaller chunks for efficient retrieval.
* Generates embeddings using Hugging Face.
* Stores document embeddings in ChromaDB.
* Retrieves relevant information based on the user's question.
* Uses an LLM to generate context-based answers.

## Tech Stack

* Python
* LangChain
* Docling
* ChromaDB
* Hugging Face Embeddings
* Ollama
* Llama 3

## Workflow

PDF → Document Processing → Chunking → Embeddings → ChromaDB → Retrieval → LLM → Answer

## How It Works

1. A PDF document is loaded and processed.
2. The document is divided into smaller chunks.
3. Each chunk is converted into a vector embedding.
4. The embeddings are stored in ChromaDB.
5. When a question is asked, relevant chunks are retrieved.
6. The retrieved context is provided to the LLM.
7. The LLM generates an answer based on the retrieved information.

## Purpose

This project demonstrates the basic implementation of RAG and how external document knowledge can be combined with an LLM to generate context-aware responses.
