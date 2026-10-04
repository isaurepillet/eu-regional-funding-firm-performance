# EU Regional Funding and Firm Performance

This repository contains code from an applied research project studying firms receiving **European Regional Development Fund (FEDER/ERDF)** support and constructing a comparable group of non-recipient firms.

The project combines information on FEDER-funded projects with longitudinal firm-level financial data. The empirical workflow focuses on preparing treated and control samples and implementing **propensity score matching (PSM)** before comparing firm outcomes around the receipt of funding.

## Empirical workflow

The notebooks document:

- preparation and harmonisation of firm-level financial data;
- matching FEDER beneficiaries with firm identifiers;
- construction of relative time around the year in which funding was received;
- definition of treated and untreated firms;
- construction of pre-treatment characteristics;
- propensity score matching using comparable control firms;
- balance and sample-comparability checks.

## Main notebooks

- **`data/code.ipynb`** — preparation and matching of the underlying firm-level datasets;
- **`data/PSM_preparation.ipynb`** — construction of the treated and control samples and preparation for matching;
- **`data/psmok.ipynb`** — propensity score matching and related diagnostics.

## Data

The analysis uses firm-level financial information and data on FEDER-supported projects. Some source data were accessed in the original research environment and are not included in this public repository.

The notebooks therefore preserve the empirical workflow but are **not fully reproducible from the repository alone**. Several paths still refer to the original Onyxia environment.

## Tools and methods

Python · pandas · statsmodels · scikit-learn · panel data · propensity score matching · policy evaluation

## Reproducibility note

Intermediate CSV files are included for parts of the workflow. Raw proprietary or restricted-access firm-level sources are not redistributed.
