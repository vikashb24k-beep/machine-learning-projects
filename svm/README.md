# Support Vector Machines

This folder contains Support Vector Machine notebooks for classification and regression.

## Files

| File | Description |
|---|---|
| `SVM_classifier.ipynb` | Support Vector Classifier notebook using the Iris dataset. |
| `svm_regression.ipynb` | Support Vector Regression notebook using the scikit-learn diabetes dataset, including GridSearchCV tuning. |

## Topics Covered

- Training `SVC` models for classification
- Training `SVR` models for regression
- Standardizing features with `StandardScaler`
- Splitting data into train and test sets
- Measuring model quality with classification and regression metrics
- Tuning hyperparameters with `GridSearchCV`

## Run the Notebooks

From the repository root:

```bash
jupyter notebook
```

Open either notebook inside the `svm/` folder.

## Dependencies

Install the common notebook dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
