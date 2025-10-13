# Legal Text Classification

## Overview
This project classifies U.S. Supreme Court decisions into categories using NLP and machine learning.

## Dataset
Use the Supreme Court Database (http://scdb.wustl.edu/) and place the CSV files in `data/raw/`.

## Workflow
1. Data Preprocessing
2. Topic Modeling with LDA
3. Classification using Logistic Regression and BERT
4. Evaluation

## Setup
1. Install Python dependencies:

   pip install -r requirements.txt
   
2. Run the notebooks in order:
- `01_data_preprocessing.ipynb`
- `02_topic_modeling.ipynb`
- `03_classification.ipynb`
- `04_evaluation.ipynb`

## Results
Check `results/` folder for metrics, plots, and reports.
