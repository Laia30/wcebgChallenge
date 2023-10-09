# wcebgChallenge23
# wcebleedgen Challenge

## Overview

This repository contains code and resources for the "wcebleedgen challenge," where the goal was to perform image classification and detection tasks. 

## Dataset

- **Train Dataset**: [https://zenodo.org/record/7548320#.Y8gkjeBX40F]

- **Test Dataset**: [https://drive.google.com/file/d/1Y564Ua5h62nwwut_EUxqWiRt4gLTtnkj/view]

Please download the datasets using the links above before running the code.

## Classification Metrics

For the image classification task, the following metrics were used for evaluation:

- **F1 Score**
- **Recall**
- **Precision**
- **Accuracy (ACC)**

These metrics were calculated as described in the table below (training):

| Metric        | Description                                   |   Classes 0 (B)  | Classes 1 (NB) |
|---------------|-----------------------------------------------|------------------|----------------|
| F1 Score      | Harmonic mean of precision and recall.        |    0.95          |    0.95        |
| Recall        | True positive rate (Sensitivity).             |    0.94          |    0.97        |
| Precision     | Positive predictive value.                    |    0.97          |    0.94        |
| Accuracy (ACC)| Ratio of correctly predicted instances.       |    0.95          |    0.95        |    

These metrics were calculated as described in the table below (validation):

| Metric        | Description                                   |   Classes 0 (B)  | Classes 1 (NB) |
|---------------|-----------------------------------------------|------------------|----------------|
| F1 Score      | Harmonic mean of precision and recall.        |    0.91          |    0.93        |
| Recall        | True positive rate (Sensitivity).             |    0.89          |    0.94        |
| Precision     | Positive predictive value.                    |    0.93          |    0.91        |
| Accuracy (ACC)| Ratio of correctly predicted instances.       |    0.92          |    0.92        |  

## Purpose
This repository is dedicated to addressing the "wcebleedgen challenge," focusing on image classification and detection tasks. Our objectives include:

- To participate in the "wcebleedgen challenge" and address the image classification and detection tasks.
- To develop and evaluate deep learning models for binary classification of medical images.
- To contribute to the field of medical image analysis and potentially improve diagnostic accuracy.

## Code Structure

# Classification
The code in this repository is organized as follows:

- `libraries.ipynb`: Contains libraries.
- `data.ipynb`: Notebooks for data preprocessing and loading.
- `models.ipynb`: houses the trained models or the model architecture, featuring "effb2" (EfficientNetB2 (pretrained)) combined with Conv2D layers for classification.
- `utils.ipynb`: Utility functions.
- `main.ipynb`: Notebook for the classification and detection tasks are performed.
- `result.ipynb`: for result analysis.

The "effb2" model, based on EfficientNetB2, is used in combination with Conv2D layers for the image classification task.
