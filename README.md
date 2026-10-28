# Titanic ML foundations

Three notebooks working through Jeremy Howard's Kaggle Titanic series (fast.ai), rebuilt to run locally on Windows (Python, pandas 3, CPU-only PyTorch).

| Notebook | What it covers | Kaggle public score |
|---|---|---|
| `pytorch_from_scratch.ipynb` | Logistic regression, then 2-layer and deep nets, built with raw PyTorch tensors, gradients and a hand-written training loop | 0.778 |
| `why_use_a_framework.ipynb` | The same problem with fastai `TabularPandas` and `tabular_learner`, learning-rate finder and a 5-model ensemble | 0.768 |
| `how_random_forests_work.ipynb` | Binary splits, OneR, decision trees, bagging by hand, then scikit-learn `RandomForestClassifier` and feature importance | 0.756 |

Every code cell has plain-language comments. The notebooks are re-runnable top to bottom.

## Setup
Download the data with the Kaggle CLI (`kaggle competitions download -c titanic`) and unzip it into `titanic/`. The data is not included in this repo.
