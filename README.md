# California Homelessness Prediction Challenge — Neural Net (K-Fold + Tuning)

**Kaggle competition:** https://www.kaggle.com/competitions/california-homelessness-prediction-challenge  
**My Kaggle notebook:** https://www.kaggle.com/code/darcy59/cah-kim-neuralnet-kfold-with-tuning

## Overview
This project documents my Kaggle workflow for the **California Homelessness Prediction Challenge**.
My focus was building a solid modeling pipeline with:
- clean preprocessing for tabular features
- a **neural network** model
- **K-Fold cross-validation** for stability
- **hyperparameter tuning** to improve performance

## What I did
- **Preprocessing:** handle missing values, scale/encode features as needed
- **Modeling:** neural network architecture + training loop settings
- **Validation:** K-Fold CV to measure performance across splits (not just one holdout)
- **Tuning:** iterate on key hyperparameters (learning rate, layers/units, epochs, regularization)

## Files (suggested structure)
- `notebooks/`  → exported Kaggle notebook (.ipynb)
- `src/`        → helper code (optional)
- `images/`     → screenshots (CV results, loss curves, feature notes)

## Reproduce
1) Open the Kaggle notebook link above and run all cells
2) (Optional) export the notebook and place it in `/notebooks/`

## Author
Darcy (Kaggle: https://www.kaggle.com/darcy59)
