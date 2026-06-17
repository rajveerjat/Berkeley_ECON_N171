# ECON N171: Economic Development — Python Notebooks
**UC Berkeley | Summer 2026 | Rajveer Jat**

This repository contains Python/Google Colab notebooks for **ECON N171**, taught at UC Berkeley. Each notebook is self-contained, requires no local installation, and is designed to run end-to-end in Google Colab in under 50 minutes.

---

## Course Overview

ECON N171 is an upper-division course exploring the economics of development through the lens of modern empirical methods. Lectures pair economic theory with hands-on replication of landmark studies — structural transformation, migration, returns to education, rural infrastructure, conditional cash transfers, and more. Students leave with both substantive knowledge and a working toolkit in causal inference and applied econometrics.

---

## Quick Start

All notebooks run on **Google Colab** — no local setup required.

1. Click the **Open in Colab** badge next to any lecture below
2. Go to `File → Save a copy in Drive` to save your own editable version
3. Run the setup cell at the top of each notebook (mounts Google Drive and installs dependencies)
4. All data is either synthetic or fetched automatically — no manual downloads needed

> **Note:** Each notebook uses a single `DATA_PATH` variable at the top. If you mount your own Drive, update this path once and everything downstream will work.

---


---

## Repository Structure

```
econ-n171/
├── lectures/
│   ├── L01_intro.ipynb
│   ├── L02_structural_transformation.ipynb
│   ├── L03_migration.ipynb
│   └── ...
├── data/
│   └── README.md          # Data sources and access notes
├── utils/
│   └── helpers.py         # Shared plotting and estimation utilities
└── README.md
```

---

## Dependencies

All notebooks install dependencies automatically in Colab. Core packages used:

- `numpy`, `pandas`, `matplotlib`, `seaborn`
- `statsmodels` — OLS, IV, ARDL, cointegration tests
- `linearmodels` — 2SLS, panel estimators
- `scikit-learn` — LASSO, cross-validation
- `econml` — Double LASSO / partially linear models
- `scipy` — statistical tests

---

## Instructor

**Rajveer Jat, PhD**
Lecturer, Department of Economics — UC Berkeley (Summer 2026)

Research: supervised factor models, sufficient dimension reduction, causal inference, economic development.

🌐 [rajveerjat.com](https://rajveerjat.com) &nbsp;|&nbsp; 💼 [LinkedIn](#) &nbsp;|&nbsp; 📧 Contact via course portal

---

## License

Notebooks are released for educational use. If you build on this material, a citation or acknowledgment is appreciated.

```
Jat, Rajveer (2026). ECON N171 Python Notebooks. UC Berkeley.
https://github.com/rajveerjat/econ-n171
```
