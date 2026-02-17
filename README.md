# IPL Final Score Prediction (Multiple Linear Regression)

This project predicts the final innings score in IPL matches using **Multiple Linear Regression**.  
The model is implemented in two ways:
1. Closed-form solution (normal equation style logic)  
2. Optimized version using **Gradient Descent from scratch**

Both approaches achieve similar performance on the dataset.

## Problem Statement
Predict the final team score using mid-innings match context:
- Score after 10 overs  
- Wickets left  

## Dataset
Ball-by-ball IPL data was processed separately to create a clean modeling dataset.  
This repository contains only the extracted features used for training and evaluation.

## Model
- Algorithm: Multiple Linear Regression  
- Optimization:
  - From scratch (closed-form logic)
  - From scratch (Gradient Descent)
- Metric: R² ≈ 0.62 (similar for both methods)

## Files
- `Multiple_LR.ipynb`  
  Training and evaluation of Multiple Linear Regression using OLS

- `dataset.csv`  

- 'Multiple_Lr_Optimise.ipynb'
  Used Gradient Descent method to optimised the model performance

  - `dataset.csv`
  Extracted features used for modeling

## What I Learned
- How multiple linear regression works internally  
- How gradient descent generalizes from simple to multiple features  
- How learning rate and iterations affect convergence  
- Why closed-form and gradient descent can reach similar optima  

## Notes
Feature engineering was done in separate scripts/notebooks.  
This notebook focuses only on **modeling and evaluation**.
