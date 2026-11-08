# KNN Iris Classification

A from-scratch implementation of the K-Nearest Neighbors (KNN) algorithm for classifying Iris flowers.

## Project Overview
The notebook compares three distance measures:
- Euclidean distance
- Manhattan distance
- Cosine distance

It includes exploratory data analysis, feature standardization, a stratified train/test split, custom KNN implementation, and model evaluation.

## Dataset
The built-in Iris dataset from scikit-learn is used. It contains four numeric flower measurements and three target classes:
- Setosa
- Versicolor
- Virginica

No external dataset download is required.

## Project Structure
```text
KNN-Iris-Classification/
├── KNN_Iris_Classification.ipynb
├── README.md
└── requirements.txt
```

## Installation
```bash
pip install -r requirements.txt
```

## Run
Open `KNN_Iris_Classification.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab and run the cells from top to bottom.

## Methodology
1. Load and explore the Iris dataset.
2. Split the data using stratified sampling.
3. Standardize features using training data only.
4. Implement Euclidean, Manhattan, and cosine distance functions.
5. Implement KNN from scratch with majority voting.
6. Compare performance using accuracy, precision, recall, F1-score, and confusion matrices.

## Technologies
Python, NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.

## Notes
The KNN classifier and distance functions are implemented manually. Scikit-learn is used for dataset loading, preprocessing, and evaluation utilities.
