# Experiment 5 — Retrieval-Augmented Generation (RAG)

## Objective
To build a system that improves LLM reliability using external knowledge retrieval.

---

## System Architecture

Query → Embedding → Retrieval → Context Injection → LLM → Response

---

## Key Components

- SentenceTransformer for embeddings
- Cosine similarity for retrieval
- Gemini API for generation

---

## Experiments Conducted

1. Retrieval quality analysis  
2. LLM without RAG (baseline)  
3. LLM with RAG  
4. Failure case analysis  
5. Top-k sensitivity  

---

## Results

- RAG significantly improves factual accuracy  
- Reduces hallucination  
- Performance depends heavily on retrieval quality  

---

## Failure Modes

- Poor query → poor retrieval → poor output  
- Irrelevant documents degrade performance  

---

## Conclusion

RAG transforms LLMs from generative systems into **grounded reasoning systems**.