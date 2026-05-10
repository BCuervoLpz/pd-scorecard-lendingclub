# PD Scorecard on Lending Club

End-to-end probability of default (PD) scorecard built on the Lending Club Loan Dataset (2007–2018), as a portfolio project for credit risk modeling.

## Goals

- Build a logistic regression PD model with WOE-transformed features.
- Scale the model output to a 300–850 score range using standard scorecard parameters (PDO=20, base score=600, base odds=50:1).
- Backtest the model with Gini, KS and PSI on a temporal out-of-time validation set.
- Deliver a model memo documenting methodology, results and limitations, in line with industry standards for internal model documentation.

## Project structure
pd-scorecard-lendingclub/
├── data/
│   ├── raw/          (gitignored, original Lending Club CSV)
│   └── processed/    (gitignored, intermediate datasets)
├── notebooks/        (Jupyter notebooks: EDA, feature engineering, modeling, backtesting)
├── src/              (reusable Python modules)
├── models/           (gitignored, pickled trained models)
├── reports/          (model memo, figures, summary docs)
├── docs/             (project journal and supporting documentation)
├── requirements.txt
├── .gitignore
└── README.md

## Stack

Python 3.11 · pandas · numpy · scikit-learn · statsmodels · optbinning · scorecardpy · matplotlib · seaborn · JupyterLab

## Status

Project in active development. See `docs/bitacora.md` for the development journal.

## Author

Borja Cuervo · [github.com/BCuervoLpz](https://github.com/BCuervoLpz)