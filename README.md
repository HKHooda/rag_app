# RAG App

This application demonstrates RAG system functionality.

## Overview

This project showcases a complete implementation of a Retrieval-Augmented Generation (RAG) system. RAG combines the power of large language models with external knowledge retrieval to provide accurate, contextually relevant responses grounded in your data.

## ✨ Features

- **Efficient Document Retrieval**: Bi-encoder technology for fast similarity search across millions of documents
- **Smart Reranking**: Cross-encoder for precise ranking of retrieval results
- **Grounded Responses**: LLM-generated answers based exclusively on retrieved documents
- **Scalable Architecture**: HNSW indexing for handling large-scale document collections
- **Interactive Jupyter Notebooks**: Explore and experiment with the RAG pipeline
- **Production-Ready Design**: Extensible architecture for real-world applications

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Required Python packages (see requirements.txt)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/HKHooda/rag_app.git
cd rag_app
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebooks:
```bash
jupyter notebook
```

## 📁 Project Structure

```
rag_app/
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── notebooks/
    └── *.ipynb              # Jupyter notebooks with RAG demonstrations
```

## 💡 Usage

Open the Jupyter notebooks to explore and run the RAG system demonstrations. Each notebook is self-contained and includes detailed explanations of the RAG workflow, component interactions, and practical examples.

### Basic Workflow

1. **Load Documents**: Import your knowledge base into the system
2. **Build Index**: Create HNSW indices for efficient retrieval
3. **Query Processing**: Submit queries to retrieve relevant documents
4. **Reranking**: Apply cross-encoder for precise ranking
5. **Generation**: Generate contextually grounded responses using GPT

## 🔍 RAG Architecture

### Components

- **Bi-Encoder**: Fast semantic search across document collections
- **Cross-Encoder**: Precise relevance scoring for top retrieval candidates
- **LLM Integration**: GPT-based generation with retrieval augmentation
- **Vector Store**: HNSW-indexed storage for scalable retrieval

### Pipeline

```
User Query
    ↓
Bi-Encoder Retrieval
    ↓
Cross-Encoder Reranking
    ↓
Context Augmentation
    ↓
LLM Generation
    ↓
Grounded Response
```

## 📚 Key Concepts

- **Retrieval**: Efficiently find relevant documents from a knowledge base
- **Augmentation**: Incorporate retrieved context into the LLM prompt
- **Generation**: Produce accurate responses grounded in retrieved information
- **Grounding**: Responses are backed by actual documents, reducing hallucinations

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
