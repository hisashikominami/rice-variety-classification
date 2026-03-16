# Rice Variety Classification

This project compares statistical and machine learning methods for classifying two Turkish rice varieties (Cammeo and Osmancik) using morphological features extracted from rice grain images. Models evaluated include logistic regression, linear discriminant analysis, quadratic discriminant analysis, decision trees, random forest, XGBoost, and support vector machines.

## Key Result

Quadratic discriminant analysis achieved competitive performance on the independent test set, while support vector machines achieved the highest cross-validated accuracy. Overall, differences in model performance were small, highlighting the importance of statistical comparison and model interpretability in addition to predictive accuracy.

## Methods

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- 10-fold cross-validation
- Independent test set evaluation
- Monte Carlo cross-validation

## Files

- `rice-variety-classification.Rmd` — full analysis
- `rice-variety-classification.pdf` — final knitted report
- `data/Rice_Cammeo_Osmancik.arff` — dataset used in the analysis

## Data Source

The dataset was obtained from the UCI Machine Learning Repository and contains 3,810 observations with seven continuous predictors describing rice grain morphology.

## Reproducibility

To reproduce the analysis, open the project in RStudio, ensure required packages are installed, and knit `rice-variety-classification.Rmd` to PDF.
