# Microsoft-AI-Model-Choice-Iris-Dataset# (AI Model Choice)

## Aim
To identify the appropriate AI model type based on dataset characteristics using the UCI Iris Dataset.

## Dataset
UCI Iris Dataset
https://archive.ics.uci.edu/ml/datasets/iris

## Objective
To determine whether supervised or unsupervised learning should be used and select the correct model type.

## Procedure
Step 1: Load Iris dataset.
Step 2: Read feature values.
Step 3: Check for labeled output column.
Step 4: Identify machine learning type.
Step 5: Select classification model.
Step 6: Display result.

## Algorithm
Step 1: Start the program.
Step 2: Load dataset.
Step 3: Read features and labels.
Step 4: Check if labels exist.
Step 5: If labels exist:
            Select supervised learning.
Step 6: Select classification model.
Step 7: Display result.
Step 8: Stop program.

## Code Logic
if labels_present:
    model = "Classification Model"

## Python Code
import pandas as pd
url = "https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data"
data = pd.read_csv(url)
print("Classification Model")

## Output
Classification Model

## Result
Supervised classification model selected successfully.

## Industry Application
Microsoft Azure ML uses classification models for prediction tasks.

## Tools Used
Python
Google Colab
GitHub
