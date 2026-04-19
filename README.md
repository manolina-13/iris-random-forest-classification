# Iris Flower Classification using Random Forest

This repository contains a Jupyter Notebook that builds and evaluates a **Random Forest Classifier** on the classic **Iris dataset**.

## File

- `RandomForest_Iris_Classification.ipynb` — Main notebook for data loading, training, evaluation, and hyperparameter tuning (`n_estimators`).

## What this notebook does

- Loads the Iris dataset from `sklearn.datasets`
- Splits data into train/test sets
- Trains a baseline Random Forest model (`n_estimators=10`)
- Tunes `n_estimators` over a range of values
- Plots accuracy vs number of trees
- Reports best accuracy and best number of trees

## Tech stack

- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib

## How to run

1. Open the notebook in Jupyter Notebook / JupyterLab / VS Code.
2. Run all cells from top to bottom.
3. Check the final output cells for best score and optimal `n_estimators`.

## Notes

- This is an educational machine learning assignment notebook.
- The cleaned notebook version removes personal semester details for public GitHub sharing.
