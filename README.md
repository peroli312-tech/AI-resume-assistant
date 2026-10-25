# AI Resume Assistant

A RAG (Retrieval-Augmented Generation) based assistant built with Python and Streamlit, developed during a GenAI workshop.

## Live Demo
https://ai-resume-assistant.streamlit.app

## How it works
1. Documents are split into chunks (`chunking.py`)
2. Chunks are converted to embeddings (`embedding_service.py`)
3. Embeddings are stored and searched in a vector store (`vector_store.py`)
4. The most relevant chunks are passed to the language model to generate an answer (`rag_service.py`)
5. Users interact through a Streamlit web interface (`streamlit_app.py`)

## Tech Stack
Python, Streamlit, Embeddings, Vector Store, Generative AI
Add exact LLM / embedding model / vector store names here

## Run locally
pip install -r requirements.txt
streamlit run streamlit_app.py

## Note
API keys are stored in environment variables / Streamlit Secrets, not in the code.
