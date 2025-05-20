# Mini_RAG_and_Knowledge_Graph
Mini projects on semantic search using ChromaDB — includes a RAG pipeline and a knowledge graph with query answering.

# Semantic Search Projects: RAG & Knowledge Graph

This repository contains two mini projects focused on **semantic search** using **ChromaDB** and **sentence-transformers**. These assignments demonstrate basic implementations of:
1. **Retrieval-Augmented Generation (RAG) Pipeline**
2. **Knowledge Graph Construction with Semantic Query Answering**



## Contents

### Assignment 1: Mini RAG Pipeline with ChromaDB

- Preprocesses short hardcoded documents (lowercase + no punctuation)
- Uses `sentence-transformers` to embed documents
- Stores embeddings in **ChromaDB**
- Accepts a user query and retrieves the most relevant document using cosine similarity

**Technologies used:**  
`sentence-transformers`, `chromadb`, `scikit-learn`


### Assignment 2: Knowledge Graph with Semantic Search

- Builds a simple RDF knowledge graph using `rdflib`
- Converts RDF triples into human-readable sentences
- Embeds the sentences using `sentence-transformers`
- Stores and queries them using **ChromaDB**
- Accepts natural language questions and returns relevant facts

**Technologies used:**  
`rdflib`, `sentence-transformers`, `chromadb`

