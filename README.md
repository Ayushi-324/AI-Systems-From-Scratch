# AI Systems From Scratch

A structured exploration of how modern AI systems actually work — from optimization dynamics to production-grade architectures like Retrieval-Augmented Generation (RAG).

This repository is designed to move beyond API usage and demonstrate a **mechanistic understanding of machine learning and AI systems**.

---

## Motivation

Most AI projects focus on using pre-built tools.

This repository takes a different approach:

* Build systems from first principles
* Analyze internal behavior
* Study failure modes
* Validate assumptions through experiments

---

## Repository Structure

```
ai-systems-from-scratch/
│
├── experiment-01-optimization/
├── experiment-02-representation/
├── experiment-03-generalization/
├── experiment-04-attention/
├── experiment-05-rag/
```

Each experiment contains:

* `notebook.ipynb` → implementation + experiments
* `observations.md` → distilled insights
* `README.md` → structured explanation
* `plots/` → visual artifacts

---

## Experiments

### 1. Optimization Dynamics

Understanding how learning rate affects training stability, convergence, and weight behavior.

**Key Takeaways**

* Learning rate controls convergence and stability
* High LR → divergence
* Low LR → slow learning
* Optimization failures prevent learning entirely

---

### 2. Representation Learning

Visualizing how neural networks transform data into separable feature spaces.

**Key Takeaways**

* Neural networks reshape data geometry
* Hidden layers progressively structure representations
* Separability is created, not given

---

### 3. Generalization vs Overfitting

Analyzing why models fail on unseen data despite strong training performance.

**Key Takeaways**

* Overfitting = memorization, not learning
* Data size and regularization are critical
* Generalization is the real objective

---

### 4. Attention Mechanism

Understanding how transformers dynamically focus on relevant information.

**Key Takeaways**

* Attention = information routing mechanism
* Tokens influence each other dynamically
* Multi-head attention captures diverse patterns

---

### 5. Retrieval-Augmented Generation (RAG)

Building a production-relevant AI system that combines retrieval with generation.

**Key Takeaways**

* Retrieval quality determines system performance
* RAG reduces hallucination
* Real-world AI systems are retrieval + reasoning pipelines

---

## Core Themes

Across all experiments:

* Optimization governs learning behavior
* Representation defines model capability
* Generalization determines real-world performance
* Attention enables contextual reasoning
* Retrieval enables reliability

---

## What This Demonstrates

This repository showcases:

* Ability to break down complex systems
* Understanding of model internals
* Experimental thinking and validation
* Awareness of real-world failure modes
* Transition from models → systems

---

## How to Run

Some experiments (e.g., RAG) require an API key.

Set your key before running:

```python
import os
os.environ["GEMINI_API_KEY"] = "your_api_key_here"
```

---

## Final Note

This is not a collection of projects.

It is a structured attempt to understand:

> how AI systems learn, transform data, fail, and scale into real-world applications.

---
