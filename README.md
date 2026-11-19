# Heart Disease Classification — Statistical Learning Study

> An academic R Markdown study comparing classification techniques using tabular heart-disease indicators.

**Domain:** supervised classification · exploratory data analysis · model evaluation  
**Tools represented:** R · caret · pROC · MASS · randomForest · Boruta

## Study overview

The source analysis explores clinical dataset variables such as age, chest-pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG indicators, maximum heart rate, exercise-induced angina and related measurements.

It includes exploratory visualizations, statistical discussion, model training and validation, feature selection, and classification metrics.

## Techniques in the notebook

- Descriptive analysis and visualizations of explanatory variables.
- Estimation/validation/test splitting and numerical normalization.
- Feature selection, including Boruta-based analysis.
- Classification approaches including linear discriminant analysis and random forest.
- Confusion-matrix analysis, accuracy, precision, recall, F1-score and misclassification rate.

## Files

| File | Description |
| --- | --- |
| `Heart-Failure-Diagnosis-Classification-.Rmd` | Original editable study |
| `Heart-Failure-Diagnosis-Classification-.pdf` | Rendered academic report |
| `Heart-Failure-Diagnosis-Classification-.vsdx` | Supporting Visio diagram |
| `heart.csv` | Dataset supplied with the original project |

## Running the analysis

1. Install R and optionally RStudio.
2. Open `Heart-Failure-Diagnosis-Classification-.Rmd` from this repository.
3. Install the R packages referenced in the document, including `knitr`, `kableExtra`, `dplyr`, `GGally`, `ggplot2`, `caret`, `e1071`, `pROC`, `readr`, `skimr`, `Boruta`, `MASS`, `rpart`, `rpart.plot` and `randomForest`.
4. Run the analysis with the working directory set to the repository root so that `heart.csv` can be loaded.

Some chunks may require adjustments to work with current versions of R packages. No fresh end-to-end run is claimed here.

## Scientific and reproducibility notes

- Dataset associations and classification scores do not establish clinical utility or causal effects.
- Any model presented for further study should document leakage checks, cross-validation, uncertainty and potential sampling bias.
- Clinical features and interpretations require careful domain verification.
- This project is an educational ML exercise and **must not be used to diagnose or guide treatment**.

## Authorship and attribution

The original R Markdown report lists **Kosar Ghazali** as its author. This repository is presented as an academic project with the original attribution preserved; individual contributions should be clarified before describing it as solo work in a job application.

The original dataset's provenance and licensing should also be verified before reuse.

**Project status:** Archived academic study; not validated for medical use.
