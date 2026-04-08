# Experiment 1 — Optimization Dynamics

## Objective
To understand how learning rate affects model training, stability, and convergence.

---

## Core Idea

Optimization determines whether a model learns effectively or fails during training.

---

## System Flow

Data → Model → Loss → Gradient → Parameter Update

---

## Experiments Conducted

1. Stable learning rate  
2. High learning rate (divergence)  
3. Low learning rate (slow convergence)  
4. Weight distribution analysis  
5. Weight norm growth  

---

## Results

- Proper learning rate ensures stable convergence  
- High learning rate leads to divergence  
- Low learning rate slows training significantly  

---

## Failure Modes

- Exploding gradients  
- Vanishing updates  
- Poor convergence  

---

## Conclusion

Optimization is the foundation of all learning — without stable training, no model can succeed.