# Confusable-Expressions

## Overview
The purpose of this Jupyter Notebook is to demonstrate how to use probabilistic models to solve word confusion errors in textual data. It uses bigram and trigram models to predict and correct confusion errors among homophones like "their", "there", and "they're".

## Features
- **Probabilistic Models**: Utilizing bigram and trigram models to handle word confusions.
- **Data Preprocessing**: Normalizing sentences and preparing them for model training.
- **Model Training and Evaluation**: Training the model on a given corpus and evaluating its performance on a test set.
- **Automated Testing**: Includes unit tests to ensure proper functionality.

## Usage
- Execute each cell sequentially from top to bottom.
- Modify parameters or data paths as necessary.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `ipykernel`, `ipytest`, and other Python standard libraries.

## Input
- **Training Data**: A set of sentences with correct usage of the target words.
- **Test Data**: A set of sentences used to evaluate the model's performance.

## Output
- The percentage of correctly resolved confusions in the test dataset.
- Detailed performance metrics of the model.

## Notes
- Ensure that all dependencies are installed before running the notebook.
- This is a lower-level understanding of probabilistic language models and Python programming.