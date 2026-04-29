# 📊 Seaborn Beginner-to-Pro — Visual EDA Guide

A practical Seaborn tutorial for exploratory data analysis: from beginner plots to cleaner comparisons, faceting, density views, heatmaps, and a compact Titanic EDA workflow.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](#)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](#)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visual%20EDA-4c72b0)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## ✅ What’s inside

- Beginner-friendly Seaborn examples with short, reusable cells
- Distribution, categorical, relationship, time-series, and faceted plots
- Version-safe snippets for Seaborn API differences such as `ci` vs `errorbar`
- Advanced visual patterns: `pairplot`, `jointplot`, `regplot`, `lmplot`, `ECDF`, `hexbin`, and masked correlation heatmaps
- A compact Titanic EDA mini-pipeline with a note on target-mirror leakage
- A final cheat sheet mapping analytical goals to Seaborn functions

---

## 📓 Main notebook

- [`seaborn-beginner-to-pro.ipynb`](seaborn-beginner-to-pro.ipynb)

Kaggle version:

- https://www.kaggle.com/code/tarekmasryo/seaborn-beginner-to-pro

---

## 📂 Data

This project uses Seaborn built-in sample datasets loaded with:

```python
sns.load_dataset(...)
```

Datasets used:

- `tips`
- `penguins`
- `flights`
- `iris`
- `titanic`

> Note: `sns.load_dataset()` may require internet access on the first run because Seaborn downloads the sample datasets.

---

## 🚀 Run locally

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook in Jupyter, JupyterLab, VS Code, or Kaggle and run it top-to-bottom.

---

## 📁 Repository layout

```text
.
├── seaborn-beginner-to-pro.ipynb
├── CASE_STUDY.md
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧠 Why this notebook exists

The goal is not to memorize every Seaborn function. The goal is to build judgment around plot selection:

- Which plot answers the current question?
- When is a simple chart better than a complex one?
- When should hue, facets, scales, or statistical helpers be added?
- Which visual patterns can mislead if used carelessly?

---

## 🧾 Case study

See [`CASE_STUDY.md`](CASE_STUDY.md) for the project story, design decisions, and publishing notes.
