# Periodic Table Elements — Metal vs Non-metal Classification

## Overview
This repository contains a Jupyter Notebook that classifies chemical elements from the periodic table into **metals** and **non-metals** using a Random Forest binary classifier. The model is trained on electronic configuration features, number of valence electrons (`Nvalence`) and the total number of electrons.

## Key features
- Binary classification of elements into metal (1) and non-metal (0).
- Two modelling approaches:
  - Using full electron configuration features.
  - Using `Nvalence` and `TotalElectrons`.
- Model evaluation with accuracy scores.
- 2D visualisations with PCA and decision boundary plots.
- Reproducible workflow in a single Jupyter Notebook.

## Results (example from notebook run)
- Classifier 1 (electron configuration) accuracy: **0.86**
- Classifier 2 (`Nvalence`, `TotalElectrons`) accuracy: **0.83**

The idea and dataset were provided by V. D. Neverov.

