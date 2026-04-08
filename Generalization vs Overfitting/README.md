# Experiment 3 — Overfitting vs Generalization

## Objective
To understand why models fail on unseen data despite performing well during training.

---

## Core Idea

A model can memorize training data instead of learning patterns, leading to poor generalization.

---

## System Flow

Data → Train/Test Split → Model Training → Loss Tracking → Evaluation

---

## Experiments Conducted

1. Small dataset overfitting  
2. Larger dataset generalization  
3. Decision boundary comparison  
4. Regularization (Dropout)  

---

## Results

- Small data leads to memorization  
- Larger data improves generalization  
- Dropout reduces overfitting  

---

## Failure Modes

- High model capacity + low data  
- Lack of regularization  
- No validation monitoring  

---

## Conclusion

Generalization is the central challenge in machine learning, not training accuracy.