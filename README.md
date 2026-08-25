# Income Classification Using PySpark

## Overview

This project develops an end-to-end machine learning workflow to classify whether an individual's annual income is above or below $50,000 using the UCI Adult Census Income dataset.

The project combines technical data-science methods with business-oriented interpretation.

## Business Question

**Can demographic, educational, employment and financial characteristics be used to distinguish between individuals earning more than $50,000 and those earning $50,000 or less?**

## Technical Workflow

1. Data acquisition
2. Data quality assessment
3. Missing-value treatment
4. Duplicate removal
5. Exploratory Data Analysis
6. Feature engineering
7. String indexing and one-hot encoding
8. PySpark preprocessing pipeline
9. Decision Tree baseline
10. Deeper Decision Tree
11. Random Forest
12. Model comparison
13. Confusion matrix analysis
14. Feature importance
15. Business interpretation
16. Ethical and model limitations

## Dataset

**UCI Machine Learning Repository — Adult Dataset**

DOI: https://doi.org/10.24432/C5XW20

The raw dataset is not stored in this repository. See [`data/README.md`](data/README.md).

## Models

- Decision Tree — baseline, `maxDepth=5`
- Decision Tree — deeper model, `maxDepth=8`
- Random Forest — 150 trees, `maxDepth=8`

The final model is selected programmatically using F1-score, with AUC as the secondary criterion.

## Evaluation

Because the target is imbalanced, the project evaluates:

- Accuracy
- Precision
- Recall
- F1-score
- AUC
- Confusion matrix

Accuracy is not treated as the only indicator of model quality.

## Business Value

The project demonstrates how machine-learning outputs can be translated into business insights for:

- workforce and labour-market analysis
- socioeconomic segmentation
- analytical research
- resource allocation studies
- understanding characteristics associated with income segments

The model is not intended for high-stakes individual decision-making.

## Ethical Considerations

The dataset contains demographic variables, including race and sex. These variables may reflect historical inequalities and can create fairness risks. Feature importance is predictive rather than causal, and model performance may not generalise to other countries or current populations.

## Technologies

- Python
- PySpark
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Machine Learning
- Google Colab / Jupyter

## Repository Structure

```text
income-classification-pyspark/
├── income_classification_pyspark.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── README.md
└── docs/
    └── PROJECT_SUMMARY.md
```

## Author

**Reitumetse Mathabathe**

Postgraduate Diploma in Data Science | Business Management

This project is part of a professional data-science portfolio.
