# breast-cancer-relapse-cnn
# Breast Cancer Relapse Prediction using CNN

## Overview
This project uses a 1D Convolutional Neural Network (CNN) to predict breast cancer relapse using gene expression data.

## Dataset
- Source: NCBI GEO (GSE2034)
- 286 patients
- Binary classification: relapse vs non-relapse

## Methods
- Data preprocessing (normalization, merging clinical data)
- 1D CNN implemented in PyTorch
- BCEWithLogitsLoss + Adam optimizer

## Results
- Accuracy: 0.793
- Precision: 0.769
- Recall: 0.526
- ROC-AUC: 0.879

## Key Findings
- Strong overall performance
- Low recall due to class imbalance

## Future Work
- Improve recall (SMOTE, class weights)
- Deeper CNN architecture
- Feature selection / gene pathways



## Author
Aavash
