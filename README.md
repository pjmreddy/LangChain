# LangChain Practice

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-Latest-green)](https://python.langchain.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-orange)](https://openai.com/)

This repository contains practice implementations from the [LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) course by DeepLearning.AI in collaboration with LangChain. It demonstrates practical applications of LangChain for building powerful RAG (Retrieval Augmented Generation) systems.

## 🎯 Course Overview

These notebooks demonstrate key concepts from the course, implementing various LangChain functionalities for building RAG (Retrieval Augmented Generation) applications. Each notebook focuses on a specific aspect of the RAG pipeline, from document processing to question answering.

## 📁 Project Structure

- `Document-Loading.ipynb`: Practice implementation of document loading techniques
  - PDF processing
  - Text file handling
  - Multiple format support

- `Document-Splitting.ipynb`: Exploration of text splitting strategies
  - Recursive character text splitting
  - Chunk size optimization
  - Overlap configuration

- `vectorstores_and_embeddings.ipynb`: Vector embeddings implementation
  - OpenAI embeddings integration
  - ChromaDB setup and usage
  - Similarity search techniques

- `Retrieval.ipynb`: Vector store retrieval methods
  - Similarity search implementation
  - Query optimization
  - Result ranking

- `Augumented_Generation(Q&A).ipynb`: RAG-based Q&A systems
  - Context-aware responses
  - Answer generation
  - Response quality optimization

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API key
- Jupyter Notebook environment

### Installation

1. Clone the repository:
```bash
git clone 
cd LangChain
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory with your OpenAI API key:
```bash
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 🛠️ Features Implemented

### Document Processing
- **Document Loading**: Support for multiple document formats (PDF, TXT)
- **Text Splitting**: Advanced chunking with recursive character text splitting
- **Chunk Optimization**: Configurable chunk sizes and overlap for optimal context

### Vector Operations
- **Embeddings Generation**: OpenAI-powered text vectorization
- **Vector Store**: ChromaDB integration for efficient similarity search
- **Query Processing**: Optimized retrieval strategies

### Question Answering
- **Context-Aware Responses**: Intelligent answer generation using RAG
- **Response Quality**: Enhanced answer relevance and accuracy
- **Interactive Chat**: Real-time Q&A capabilities

## 📦 Dependencies

### Core Packages
- `langchain>=0.0.9`: Main framework for RAG applications
- `openai>=1.0.0`: OpenAI API integration
- `chromadb>=0.4.18`: Vector store implementation
- `pypdf>=3.17.1`: PDF document processing

### Additional Tools
- `python-dotenv>=0.21.0`: Environment variable management
- `jupyter>=1.0.0`: Notebook interface
- `pandas>=2.1.0`: Data manipulation
- `numpy>=1.24.0`: Numerical operations

For a complete list with versions, see `requirements.txt`

## 📝 License and Attribution
This repository contains practice implementations from the [LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) course. All course materials and concepts are owned by DeepLearning.AI and LangChain.

- This project is for educational purposes only
- Not for commercial use
- Please respect all applicable licenses and terms of use

## 🙏 Acknowledgments

This project wouldn't be possible without:

- **DeepLearning.AI**: For creating the comprehensive course material
- **LangChain Team**: For their innovative framework and collaboration
- **OpenAI**: For providing the API that powers the embeddings and completions
- **ChromaDB Team**: For their efficient vector store implementation

## 📫 Contributing

While this is primarily a learning project, suggestions and improvements are welcome:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request