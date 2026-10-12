# Exercise 1: Perceptron

Implementation of a Single-Layer Perceptron using the Banknote Authentication dataset.
# Exercise 1: Perceptron-Based Decision Boundary and Linear Separability

## Overview
This project implements a menu-driven Single-Layer Perceptron (SLP) using the Banknote Authentication dataset to classify banknotes as genuine or forged. It explores decision boundaries, linear separability, feature combinations, training sample order, borderline samples, and the limitations of perceptrons on non-linearly separable data.

## Objectives
- Implement a Single-Layer Perceptron for binary classification.
- Normalize input features and encode target classes as 0 and 1.
- Explore decision boundaries and feature-pair separability.
- Investigate the effect of training sample order on classification.
- Demonstrate the XOR limitation of a single-layer perceptron.
- Evaluate classification performance and the impact of feature removal.

## Menu Options
1. Banknote Classification using Perceptron
2. Decision Boundary Explorer
3. Feature Pair Separability Challenge
4. Training Sample Order Challenge
5. Borderline Sample Detector
6. XOR Limitation Demonstrator
7. Perceptron Feature Removal Challenge
8. Perceptron Classification Report
9. Exit

## Dataset
The Banknote Authentication dataset contains four numerical features: variance, skewness, curtosis, and entropy. The target represents the banknote class.

## Technologies
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (if used in the implementation)

## How to Run
1. Open `Exercise1.ipynb` in Google Colab.
2. Install or import the required libraries.
3. Load the Banknote Authentication dataset.
4. Run the notebook cells sequentially.
5. Select a menu option to explore the different perceptron experiments.

## Repository Structure
- `Exercise1.ipynb` — implementation and experiments
- `README.md` — project overview and instructions
- `report.md` — detailed project report
- `results/` — plots and evaluation outputs, if generated
- `requirements.txt` — Python dependencies

## Expected Learning Outcomes
Understand how a single-layer perceptron learns a linear decision boundary and how feature selection, training sample order, and non-linearly separable data affect its performance.

## Author
Nelli Akshara
