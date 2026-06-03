# Decision Tree Projects

This folder contains Decision Tree practice notebooks and a complete e-commerce purchase prediction project.

## Files

| File or Folder | Description |
|---|---|
| `decision_tree.ipynb` | Decision Tree regression notebook using the scikit-learn diabetes dataset. |
| `decision_tree_classifier.ipynb` | Decision Tree classification notebook using the Titanic dataset, with pre-pruning and post-pruning examples. |
| `decision-tree-purchase-prediction/` | End-to-end Decision Tree classification project for predicting e-commerce purchases. |

## Notebook Topics

- Loading sample datasets
- Splitting data into train and test sets
- Training Decision Tree regression and classification models
- Evaluating predictions with metrics such as R2 score, mean squared error, accuracy, and classification reports
- Applying pre-pruning and post-pruning techniques
- Visualizing model behavior and results

## Run the Notebooks

From the repository root:

```bash
jupyter notebook
```

Open either `decision_tree.ipynb` or `decision_tree_classifier.ipynb`.

## Full Project

The `decision-tree-purchase-prediction/` folder includes reusable Python modules, a dataset, model artifacts, evaluation outputs, and a Streamlit app.

Run it from that folder:

```bash
pip install -r requirements.txt
python main.py
streamlit run app/app.py
```
