# RAG
have created a RAG chatbot project using Gemma.
This project is a simple Retrieval-Augmented Generation (RAG) demo built in Google Colab. It:

Loads a .txt file (e.g., About India, cricket.txt).

Splits the text into chunks for efficient search.

Creates HuggingFace embeddings and stores them in a FAISS vector database.

Uses Groq LLM (gemma2-9b-it) to answer questions based on retrieved context.

🚀 Quick Steps

Install dependencies (langchain, faiss-cpu, langchain_groq, etc.).

Provide your Groq API Key securely.

Mount Google Drive / upload your text file.

Run the notebook cells.

Ask questions and get answers from the document.

🔑 Key Technologies

LangChain

HuggingFace Sentence Transformers

FAISS (vector store)

Groq LLM
