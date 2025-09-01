# CodeAlpha – Creditworthiness Prediction

Predict an individual's creditworthiness using past financial data.

## Dataset
- Features: income, debts, payment history, credit utilization, late payments, etc.
- Source: (add link you’ll use, e.g., a Kaggle/UCI credit risk dataset)

## Approach
- Preprocessing: missing value handling, encoding categorical features, scaling.
- Models: Logistic Regression, Decision Tree, Random Forest.
- Metrics: Precision, Recall, F1-Score, ROC-AUC.

## How to Run
1. `pip install -r requirements.txt`
2. Run `notebooks/creditworthiness.ipynb` (or `src/train.py`)  
3. Outputs: metrics report and ROC curve in `reports/`.

## Repo Structure
CodeAlpha_CreditworthinessPrediction/
│
├── notebooks/
│   └── creditworthiness.ipynb     # Jupyter notebook with full code
│
├── src/                           # (optional) Python scripts if you separate code
│   └── utils.py                   # helper functions
│
├── data/                          # (empty, or small sample) dataset folder
│   └── README.md                  # explains how/where to get dataset
│
├── reports/                       # store generated plots/metrics
│   └── roc_curve.png
│
├── requirements.txt               # list of dependencies
├── README.md                      # project explanation
└── LICENSE                        # MIT license


## Results
- 

## License
MIT
