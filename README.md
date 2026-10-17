# AI-Generated Text Detection

## Project Overview

This Natural Language Processing (NLP) project classifies text as human-written or AI-generated. It extends classical machine-learning baselines with transformer-based models, a weighted stacking ensemble, and explainability techniques.

## Models and Methods

- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- BERT (`bert-base-uncased`)
- RoBERTa (`roberta-base`)
- Logistic Regression stacking ensemble
- SHAP and LIME for explainability

## Datasets

The project uses two datasets:

1. An academic-writing dataset containing human-written and ChatGPT-generated abstracts.
2. An essay-writing dataset containing human-written and AI-generated essays.

Dataset files are not included in this repository. Obtain them from their authorized sources and place them in the paths configured in the notebook.

## Reported Results

| Model | Dataset 1 Accuracy | Dataset 2 Accuracy |
|---|---:|---:|
| SVM | 89.46% | 99.36% |
| BERT | 94.03% | 99.14% |
| RoBERTa | 93.82% | 99.38% |
| Weighted Stacking Ensemble | 95.14% | 99.51% |

These figures are reported in the final project report. Results may vary when experiments are rerun.

## Tools and Libraries

- Python
- PyTorch
- Hugging Face Transformers
- scikit-learn
- pandas and NumPy
- Matplotlib
- SHAP and LIME
- Jupyter Notebook / Google Colab

## How to Run

1. Open the notebook in Google Colab or a compatible Jupyter environment.
2. Install the dependencies listed in the notebook.
3. Upload or mount the required datasets.
4. Update the dataset paths if necessary.
5. Execute the notebook cells in order.

Transformer fine-tuning can require a GPU and considerable runtime.

## Limitations

- Maximum sequence length was set to 128 tokens.
- Hyperparameter search used a limited grid.
- SHAP and LIME explanations were evaluated on a small sample.
- Generalization to other text genres has not been established.

## Authors

Zarir Zaman, Hasibul Hasan, and Esratul Jannat Jui

American International University-Bangladesh (AIUB)

Course: Natural Language Processing
