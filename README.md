# RAG_and_SemanticSearch
Both RAG (Retrieval-Augmented Generation) and Semantic Search are modern AI techniques that utilize embeddings and vector search, but they are designed for different purposes and operate in distinct ways.

Key Difference: Semantic search focuses on retrieving relevant documents, while RAG combines retrieval with language generation to produce coherent, context-aware responses. Semantic search is ideal for fast and direct retrieval, whereas RAG excels in scenarios requiring natural language interaction.

Here we will build a semantic search engine over a PDF document. This will allow us to retrieve passages in the PDF that are similar to an input query.
The RAG notebook implements a RAG pipeline in Python using an OpenAI LLM in combination with a Weaviate vector database and an OpenAI embedding model. LangChain is used for orchestration.

For Semantic Search:
- pip install langchain-community pypdf
- pip install -qU langchain-openai
- pip install -qU langchain-core

For RAG:
pip install langchain openai weaviate-client
