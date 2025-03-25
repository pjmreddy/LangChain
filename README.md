# LangChain Practice

This repository contains practice implementations from the [LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) course by DeepLearning.AI in collaboration with LangChain.

## Course Overview

These notebooks demonstrate key concepts from the course, implementing various LangChain functionalities for building RAG (Retrieval Augmented Generation) applications.

## Project Structure

- `Document-Loading.ipynb`: Practice implementation of document loading techniques
- `Document-Splitting.ipynb`: Exploration of text splitting strategies for optimal chunking
- `vectorstores_and_embeddings.ipynb`: Implementation of vector embeddings and similarity search
- `Retrieval.ipynb`: Practice with vector store retrieval methods
- `Augumented_Generation(Q&A).ipynb`: Implementation of RAG-based question-answering systems

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file in the root directory with your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

3. Run Jupyter Notebook:
```bash
jupiter notebook
```

## Features Implemented

- Document Loading: Techniques for loading and processing various document formats
- Text Splitting: Implementation of recursive character text splitting with chunk optimization
- Vector Embeddings: Practice with OpenAI embeddings for text vectorization
- Vector Stores: Implementation of Chroma DB for similarity search
- Question Answering: Building RAG-based Q&A systems

## Dependencies

Key packages used:
- langchain and related packages (openai, community, chroma)
- openai
- chromadb
- pypdf
- python-dotenv

For a complete list, see `requirements.txt`

## License and Attribution

This repository contains practice implementations from the "LangChain: Chat with Your Data" course. All course materials and concepts are owned by DeepLearning.AI and LangChain. These implementations are for educational purposes only.

## Acknowledgments

Special thanks to:
- DeepLearning.AI for creating the course
- LangChain team for their collaboration and framework