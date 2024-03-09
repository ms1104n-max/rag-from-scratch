# RAG from Scratch - Source Library

This directory contains the reusable library code for the RAG from Scratch project, maintained by Sai Nikhil Mattapalli.

## Structure

- **embeddings/** - Text-to-vector conversion and caching
- **vector-stores/** - Vector storage and similarity search implementations
- **loaders/** - Document loading from various sources (PDF, text, etc.)
- **text-splitters/** - Strategies for chunking documents
- **retrievers/** - Document retrieval strategies
- **chains/** - RAG pipeline orchestration
- **prompts/** - Prompt template management
- **utils/** - Shared utilities and helpers

## Usage

```javascript
import {
  EmbeddingModel,
  InMemoryVectorStore,
  PDFLoader,
  RecursiveCharacterTextSplitter,
  VectorStoreRetriever,
  RAGChain
} from "./src/index.js";

// Build your RAG pipeline...
```

## Development

Each module follows these principles:
1. Single responsibility
2. Abstract base classes where appropriate
3. Consistent interfaces
4. Comprehensive error handling
5. Full JSDoc documentation

## Testing

Tests are located in the /tests directory and mirror this structure.

## Maintainer

Sai Nikhil Mattapalli is an AI/ML Engineer specializing in the development and deployment of scalable Machine Learning and Generative AI solutions. With a focus on LLMs, RAG architectures, and vector databases, he maintains this library to support the creation of modular and efficient retrieval-augmented generation pipelines.

Contact Information:
- Name: Sai Nikhil Mattapalli
- Title: AI/ML Engineer
- Email: ms1104n@gmail.com