- Simpe RAG pipeline with Reranking

- Architecture
    - User query -> Embedding search (Top 50) -> Reranking( query + chuck + score) -> Top 5 high precision chunks -> LLM -> Answer

- RAG
   - Retrieve
   - Rerank
   - Select
   - Generate

- RAG pipeline stages
    - Ingestion
    - Chunk
    - Index
    - Retrieve
    - Rerank
    - Generate