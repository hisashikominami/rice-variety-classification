# Rice Variety Classification

## Summary

This project compares statistical and machine learning methods for classifying two Turkish rice varieties (**Cammeo** and **Osmancik**) using morphological features extracted from rice grain images. The analysis applies cross-validation, test set evaluation, and Monte Carlo resampling to assess whether quadratic discriminant analysis (QDA) performs competitively relative to commonly used machine learning models. Comparing multiple modeling approaches provides a more robust understanding of predictive performance and helps identify models that balance accuracy, interpretability, and generalization.

## Key Result

Support vector machines achieved the highest cross-validated accuracy, while quadratic discriminant analysis (QDA) showed the strongest generalization with the smallest difference between cross-validated and test accuracy. Overall performance differences across models were small, indicating that a small set of geometric grain features is sufficient to accurately distinguish between the two rice varieties.

## Methods

Models evaluated in this analysis include:

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

Model performance was evaluated using:

- 10-fold cross-validation
- Independent test set evaluation
- Monte Carlo cross-validation (100 iterations)

## Skills Demonstrated

- Supervised machine learning model comparison
- Statistical classification methods (LDA, QDA, logistic regression)
- Tree-based ensemble methods (Random Forest, XGBoost)
- Model evaluation using cross-validation and Monte Carlo resampling
- Exploratory data analysis and feature interpretation
- Statistical reasoning about model performance and predictor importance
- Data analysis and modeling in R

## Repository Structure

```
rice-variety-classification/
├── rice-variety-classification.Rmd # Full analysis
├── rice-variety-classification.pdf # Final report
├── rice-variety-classification.Rproj # RStudio project file
└── data/
└── Rice_Cammeo_Osmancik.arff # Dataset used in analysis
```

## Data Source

The dataset was obtained from the UCI Machine Learning Repository and contains 3,810 observations with seven continuous predictors describing rice grain morphology.

Dataset reference:
https://archive.ics.uci.edu/ml/datasets/Rice+Cammeo+and+Osmancik

## Reproducibility

To reproduce the analysis:

1. Open the project in RStudio.
2. Install required R packages if needed.
3. Knit `rice-variety-classification.Rmd` to generate the report.
