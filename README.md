# Purpose

The purpose of this project was to create a customer support chatbot using next.js, a llama api, and ChromaDB.
We've implemented a RAG system with embedded internal documents.

## Setup

Run the ChromaDB docker container:
```
docker pull chromadb/chroma
docker run -p 8000:8000 chromadb/chroma
```

Run our app
```
npm run build
npm run start
```
