## # RAG Playground Using LlamaIndex
[streamlit-app-2024-05-09-02-05-91.webm](https://github.com/abhi2596/rag_demo/assets/80634226/b244dbdf-b292-4ab9-bf04-cfe92404c4be)

## Introduction 

The RAG Playground is an application designed to facilitate question-answering tasks based on uploaded PDF documents. It leverages LLamaIndex for RAG functionalities and utilizes Streamlit for the user interface.

## Key Features

- **PDF Upload:** Easily upload PDF files to the application.
- **Questioning:** Ask questions about the uploaded PDF documents.
- **RAG Integration:** Utilize LLamaIndex for RAG capabilities.
- **Embeddings:** Convert text to embeddings using the BAAI/bge-small-en-v1.5 model.
- **Reranker:** Reorder search results based on relevance to queries.
- **Streamlit Optimization:** Enhance performance using `@st.experimental_fragment` and `@st.cache_resource`.

## Project Workflow

1. **PDF Processing:**
   - Load PDF files and extract text using PDFReader.
   - Load data into Documents in LLamaIndex.
2. **Chunking and Conversion:**
   - Chunk text and convert it into nodes using `VectorStoreIndex.from_documents`.
   - Convert text to embeddings using the BAAI/bge-small-en-v1.5 model.
3. **Search Optimization:**
   - Implement a reranker to reorder search results based on query relevance.
   - Display top-ranked results after reranking.
4. **Interface Optimization:**
   - Build the user interface using Streamlit.
   - Optimize Streamlit performance with `@st.experimental_fragment` and `@st.cache_resource`.

## Technologies Used

- LLamaIndex
- Streamlit
- BAAI/bge-small-en-v1.5 model

## Repository and Deployment
Github - https://github.com/abhi2596/UnifyAI_RAG_playground/tree/main
Streamlit App - https://unifyai-rag-playground.streamlit.app/

Instructions to run locally:

1. First create a virtual environment in python 

```
python -m venv <virtual env name>
```
2. Activate it and install poetry 

```
source <virtual env name>/Scripts/activate - Windows
source <virtual env name>/bin/activate - Linux/Unix
pip install poetry
```
3. Clone the repo

```
git clone https://github.com/abhi2596/UnifyAI_RAG_playground/tree/main
```
4. Run the following commands

```
poetry install 
cd rag
streamlit run app.py
```

## Contributors

| Name | GitHub Profile |
|------|----------------|
| Abhijeet Chintakunta | [abhi2596](https://github.com/abhi2596) |
