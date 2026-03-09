# Hi, I'm Artem

Python backend developer focused on AI systems and backend infrastructure.

Currently building RAG systems using FastAPI, vector search, and local LLM inference.

## Main Project

### RAG Assistant

Retrieval-Augmented Generation backend with:

- FastAPI
- Qdrant vector search
- Ollama local LLM inference
- sentence-transformers
- Docker

Repository:  
https://github.com/artemdev/rag-assistant

## Architecture

```mermaid
flowchart TD
    User --> API
    API --> Retriever
    Retriever --> Qdrant
    Retriever --> Reranker
    Reranker --> LLM
    LLM --> Response
