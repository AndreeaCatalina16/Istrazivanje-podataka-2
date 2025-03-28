# Protein Disorder Prediction for MERS, EBOLA, and MARBURG Viruses

## Project Overview
This project focuses on predicting **ordered and disordered regions** in the proteins of MERS, EBOLA, and MARBURG viruses. The classification model is built using **molar fractions and fractional differences** as key features. The ordered and disordered regions are determined using three tools: **ISUNSTRUCT, VSL2B, and IUPRED3**.

## Data Collection
- Protein sequences were obtained from https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/find-data/virus.
- Disorder annotations were generated using:
  - **ISUNSTRUCT**
  - **VSL2B**
  - **IUPRED3**

## Feature 
- **Molar fractions**: The relative abundance of amino acids in the sequence.
- **Fractional differences**: Differences in molar fractions between ordered and disordered regions.

## Classification Models
The following machine learning models were used to classify ordered and disordered protein regions:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**

## Model Evaluation
- Performance was assessed using **accuracy, precision, recall, and F1-score**.
- **External validation** was performed to ensure generalization to unseen data.

