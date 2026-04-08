# Observations — RAG System

## Retrieval Quality
- Relevant documents consistently rank highest
- Semantic similarity works well for simple queries

## Without RAG
- Responses are verbose but generic
- Includes unnecessary or hallucinated details

## With RAG
- Responses are concise and grounded
- Directly use retrieved context

## Failure Case
- Irrelevant queries retrieve incorrect documents
- System fails silently → dangerous in production

## Top-K Sensitivity
- k=1 → too narrow
- k=2 → balanced
- k=3 → noisy

## Key Insight
System performance depends more on retrieval than generation.