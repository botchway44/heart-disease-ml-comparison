# Heart Disease Machine Learning Comparison

An academic machine learning project that compares classification models for heart disease detection using a public healthcare dataset.

## Project overview

The notebook explores a dataset with 920 records and 16 columns. The work includes exploratory data analysis, missing-value handling, categorical encoding, class-imbalance handling, model training, cross-validation, hyperparameter tuning, and model evaluation.

This is an educational project. It is not a clinical diagnostic system and should not be used to make medical decisions.

## Models compared

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Techniques used

- Data cleaning and exploratory data analysis
- Missing-value imputation
- Categorical feature encoding
- StandardScaler for numerical features
- SMOTENC for class balancing
- Five-fold cross-validation
- GridSearchCV for hyperparameter tuning
- Accuracy, precision, recall, F1, and confusion matrices

## Verified results

| Model | Cross-validation accuracy | Test accuracy | Weighted F1 |
|---|---:|---:|---:|
| Logistic Regression | 0.524 | 0.496 | 0.456 |
| Decision Tree | 0.569 | 0.583 | 0.586 |
| Random Forest | 0.637 | 0.626 | 0.605 |
| SVM | 0.579 | 0.578 | 0.489 |

Random Forest produced the strongest result in the initial comparison. The notebook also experiments with class balancing and hyperparameter tuning using a different training setup.

## Notebook

[Open the original notebook in Google Colab](https://colab.research.google.com/drive/1zc8kWn8g723tSsCeZC9dfp3kGynoCMkO)

## Technology

Python, pandas, NumPy, scikit-learn, imbalanced-learn, Matplotlib, Seaborn, Plotly, and Yellowbrick.

## Dataset and attribution

The project uses the public UCI Heart Disease dataset. The notebook retains the dataset creators and citation information. Any publication or reuse should preserve the original attribution and license requirements.

## Current status

The academic notebook is being cleaned for reproducibility. Planned improvements include removing repeated code, consolidating preprocessing into pipelines, rerunning all cells, and adding a final tuned-model comparison.
