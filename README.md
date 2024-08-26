# Tourism_RAG
Tour Guide RAG (Retrieval-Augmented Generation) System
This project implements a Tour Guide system using Retrieval-Augmented Generation (RAG) with the Mistral-7B-Instruct-v0.2 model and FAISS for efficient similarity search.

Dataset Link: VectorDB
Features
Uses Mistral-7B-Instruct-v0.2 as the base language model
Implements RAG for enhanced question-answering capabilities
Utilizes FAISS for fast and efficient similarity search
Provides a Gradio interface for easy interaction
Dependencies
langchain
torch
transformers
sentence-transformers
faiss-gpu
gradio
Setup
Install the required dependencies
Set up the Hugging Face API key
Load the FAISS database from the specified path
Initialize the language model and RAG pipeline
Usage
Run the script to start the Gradio interface
Enter your travel-related questions in the text box
Receive informative answers from the AI tour guide
Model Details
Base Model: Mistral-7B-Instruct-v0.2
Quantization: 4-bit quantization for efficient inference
Embeddings: sentence-transformers/all-MiniLM-L6-v2
Customization
You can customize the following aspects:

Prompt template
Model parameters (temperature, max length, etc.)
Number of retrieved documents (k value in FAISS search)
Note
This project is designed to run in a Google Colab environment with GPU support. Adjustments may be needed for local execution.
