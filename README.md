# RAG Pipeline with Webpages

## Overview

This repository contains a Jupyter notebook (`RAG_pipeline_with_webpages.ipynb`) that demonstrates a Retrieval-Augmented Generation (RAG) pipeline for ingesting webpages, creating vector embeddings, storing them in a vector store, and using an LLM to answer queries grounded in the retrieved documents.

The notebook is intended as a practical, end-to-end example you can adapt to your own data and model choices.

---

## Features

* Fetch and preprocess webpages (URL fetching, HTML cleaning, text extraction)
* Chunking / splitting documents for better retrieval performance
* Create dense embeddings using an embeddings model
* Store embeddings in a vector store (ChromaDB)
* Run similarity search (retrieval) and perform LLM-based generation over retrieved context
* Example notebook cells that demonstrate end-to-end ingestion, indexing, and question-answering

---

## Requirements

This notebook was built and tested with Python 3.9+ and the following libraries (not exhaustive):

* jupyter
* requests
* beautifulsoup4
* langchain
* openai (or other LLM provider SDK)
* sentence-transformers (optional)
* chromadb or faiss-cpu
* tiktoken (optional, for token counting)
* pandas

---

