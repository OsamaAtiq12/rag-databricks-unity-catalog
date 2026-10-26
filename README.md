# RAG from Scratch on Databricks (Unity Catalog + Vector Search)

End-to-end retrieval-augmented generation pipeline built in a Databricks notebook.

- Parse PDFs and extract structured knowledge into governed Delta tables (Unity Catalog)
- Custom text splitters: fixed-size (512/50) and semantic chunking
- Embedding generation into Delta tables and vector search with cosine top-k retrieval
- LangChain answer generation, with a measured comparison of fixed vs semantic chunking on answer quality

Files: `rag_databricks_pipeline.ipynb` (main), `bonus_extension.ipynb`.
Built as part of the MLOps course in my MS in AI at LUMS.
