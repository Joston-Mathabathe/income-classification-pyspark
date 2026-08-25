# Project Summary — Income Classification Using PySpark

## Project Objective

Develop a machine-learning classifier that predicts whether an individual's annual income is above or below $50,000.

## Data

UCI Adult Census Income dataset.

After cleaning, the existing project contains 32,537 unique observations. The target distribution is approximately 75.9% `<=50K` and 24.1% `>50K`.

## Baseline Results Already Obtained

The original notebook produced the following baseline Decision Tree results:

| Model | Accuracy | Precision | Recall | F1-score | AUC |
|---|---:|---:|---:|---:|---:|
| Baseline Decision Tree | 83.33% | 75.76% | 45.60% | 56.93% | 58.37% |
| Deeper Decision Tree | 83.53% | 66.31% | 64.76% | 65.52% | 78.58% |

The deeper Decision Tree substantially improved recall, F1-score and AUC while changing accuracy only slightly.

The final notebook additionally trains a Random Forest and selects the final model programmatically after comparing all three approaches. Run the notebook to generate the final Random Forest metrics and final model selection.

## Business Interpretation

The model can be framed as an analytical segmentation exercise rather than a tool for making decisions about individuals. The project demonstrates how technical model outputs can support business questions while considering data quality, model trade-offs and responsible use.

## Key Portfolio Skills

- PySpark
- Python
- Data cleaning
- EDA
- Feature engineering
- Machine learning
- Model evaluation
- Model comparison
- Business analytics
- Responsible AI
