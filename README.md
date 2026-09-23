# Credit Risk Model

A machine-learning project for estimating a borrower's probability of default, credit score, and risk rating. The repository contains the model-development notebook and a Streamlit application scaffold.

## Project structure

```text
.
├── app/
│   ├── main.py
│   └── prediction_helper.py
├── artifacts/
│   └── model_data.joblib
├── credit_risk_model_codebasics.ipynb
└── requirements.txt
```

The raw files under `dataset/` are intentionally excluded from Git. Confirm that the data is safe and appropriately licensed before publishing it.

## Run the Streamlit application

Create and activate a virtual environment, then install the dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Start the application from the repository root:

```bash
streamlit run app/main.py
```

## Model development

The training and evaluation workflow is documented in `credit_risk_model_codebasics.ipynb`. Regenerate `artifacts/model_data.joblib` after changing preprocessing, selected features, or the final model.

