# Learning Rate Stability in Gradient-Based Learning

## Overview
This project studies how learning rate affects training stability in gradient-based optimization.
A linear regression model was implemented from scratch using NumPy, without relying on high-level ML libraries.

Three controlled experiments were conducted:
- Stable learning rate
- Training failure due to excessive learning rate
- Recovery of stability using a reduced learning rate

The goal is to demonstrate practical understanding of optimization dynamics through experimentation rather than abstraction.

## Experiments
1. **Stable Learning (0.01)**  
   Smooth convergence with steadily decreasing loss.

2. **Failure Case (1.0)**  
   Divergence and numerical overflow caused by excessive parameter updates.

3. **Recovery (0.001)**  
   Restored stability and controlled convergence.

Each experiment is documented with loss plots and written observations.

## Tools Used
- Python
- NumPy
- Matplotlib
- Google Colab

## How to Run
Open the notebook `learning_rate_stability.ipynb` in Google Colab or Jupyter Notebook and run cells sequentially.

## Future Work
- Extend to non-linear models
- Compare optimizers such as Adam and RMSprop
- Analyze robustness under noisy data
- Package experiments into reusable modules

## Ayushi 
