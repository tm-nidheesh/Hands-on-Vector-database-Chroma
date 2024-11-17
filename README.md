# Hands-on-Vector-database-Chroma

ChromaDB is an open-source vector database designed for storing, indexing, and querying high-dimensional embeddings or vector data. It is particularly optimized for use cases involving AI, machine learning, and applications that require similarity search or context retrieval, such as Large Language Model (LLM)-based systems like ChatGPT.<br>

## Key Features of ChromaDB
* Vector Storage: Stores embeddings (numerical representations of data like text, images, or audio) in a high-dimensional vector space.
* Similarity Search: Enables searching for items (vectors) that are most similar to a given query vector, making it ideal for recommendation systems, semantic search, and personalized responses.Supports cosine similarity, Euclidean distance, and other distance metrics.
* Metadata Support: Along with embeddings, ChromaDB can store metadata (e.g., document IDs, tags, timestamps) for better context retrieval and filtering.

## How ChromaDB Works
* Embedding Generation: Data (text, images, audio) is converted into vector embeddings using AI models like OpenAI’s GPT, Hugging Face transformers, or custom models.
* Storage: These embeddings are stored in ChromaDB along with associated metadata.
* Querying:Users query the database using a new vector (e.g., an embedding of a search query or document). ChromaDB retrieves the most similar vectors based on distance metrics (e.g., cosine similarity).

## Why Use ChromaDB?
* Fast and Efficient: Optimized for vector similarity search, even with large datasets.
* Open Source: Free to use and customizable to suit specific needs.
* LLM-Friendly: Seamlessly integrates with AI workflows and retrieval-augmented generation (RAG) systems.

## Further reading and information
ChromaDB: https://docs.trychroma.com/ <br>
ChromaDB Embeddings: https://docs.trychroma.com/guides/embeddings <br>
ChromaDB Integration: https://docs.trychroma.com/integrations <br>

Kaggle Dataset: https://www.kaggle.com/datasets/asad1m9a9h6mood/news-articles
