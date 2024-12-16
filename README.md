# HR Analytics - Candidate Retention Prediction

## Overview

ScaleneWorks assists IT companies in India by predicting candidate retention rates. Approximately 30% of candidates who accept job offers fail to join, leading to significant time and revenue loss. This project aims to predict the likelihood of candidates joining post-offer acceptance, enabling companies to optimize their hiring strategy.

## Requirements

- **Python 3.x**
- **Libraries**:
  - **Numpy**: For numerical operations and array manipulation.
  - **Pandas**: For data manipulation and analysis.
  - **Seaborn**: For data visualization.
  - **Matplotlib**: For plotting and creating visualizations.

## Project Summary

This project develops a predictive model that analyzes 18 candidate attributes, including demographics and offer details, to assess whether candidates are likely to join the company. The model was trained on a dataset with no missing values.

## Model Performance

- **Accuracy**: ~82%
- **Kappa Score**: 0.64
- **AUC Score**: 0.82
- **Precision (Class 1)**: ~0.84
- **Recall (Class 1)**: ~0.76
- **F1-Score**: ~0.81

## Key Techniques

- **Feature Selection**: Identified 34 significant features and reduced multicollinearity using VIF analysis.
- **Threshold Optimization**: Adjusted the probability threshold to ~0.44, aligning false positive/negative rates with business cost implications.

## Conclusion

The model successfully predicts the likelihood of a candidate joining, offering valuable insights to reduce recruitment costs and improve hiring efficiency for IT companies.
