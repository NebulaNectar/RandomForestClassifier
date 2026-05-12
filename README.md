# RandomForestClassifier — Iris Flower Classification
Iris flower classification using Random Forest Classifier

## About the Project
This project classifies iris flowers into 3 species
using the Random Forest Classifier machine learning model.

## Dataset
- File: Iris.csv
- Rows: 150
- Columns: Id, SepalLengthCm, SepalWidthCm, 
           PetalLengthCm, PetalWidthCm, Species

## Target Classes
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Features Used
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

## Model Used
- Random Forest Classifier (from sklearn.ensemble)
- n_estimators = 100 (100 decision trees)

## Results
- Accuracy  = 100.0 %
- Precision = 1.00
- Recall    = 1.00
- F1 Score  = 1.00

## Why Random Forest?
Random Forest creates 100 decision trees and takes 
majority vote for the final prediction. It works 
very well on structured tabular data like Iris dataset.
Each tree learns from a random portion of data making 
the model more accurate and less prone to mistakes.

## Libraries Used
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## How to Run
1. Open RandomForestClassifier.ipynb in Google Colab
2. Upload Iris.csv to your Google Drive
3. Change the path variable to your file location
4. Run all cells
