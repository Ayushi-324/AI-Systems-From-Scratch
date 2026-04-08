# Observations — Generalization vs Overfitting

## Small Dataset
- Training loss drops quickly
- Test loss remains high
- Large gap indicates overfitting

## Larger Dataset
- Train and test loss are closer
- Model generalizes better

## Decision Boundary
- Overfit model → complex, irregular boundary
- Generalized model → smooth boundary aligned with data

## Regularization (Dropout)
- Reduces gap between train and test loss
- Prevents memorization

## Key Insight
Generalization depends more on data quality and constraints than model complexity.