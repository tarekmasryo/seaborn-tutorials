# 🧠 Case Study — Seaborn Beginner-to-Pro

## Problem

Build a practical Seaborn reference that helps readers move from basic plots to stronger exploratory data analysis decisions.

The notebook is designed for learners who already know basic Python and want a reusable visual EDA playbook rather than a long API catalog.

---

## Goals

- Teach plot selection through small, readable examples
- Keep each cell focused on one visual idea
- Show when to use distributions, comparisons, relationships, facets, density views, and heatmaps
- Include realistic EDA cautions such as overplotting, misleading scales, unstable means, and target-mirror leakage
- Keep the notebook lightweight enough to run on Kaggle or locally

---

## Data

The notebook uses Seaborn built-in sample datasets:

- `tips`
- `penguins`
- `flights`
- `iris`
- `titanic`

These datasets are intentionally small, familiar, and suitable for visual explanation.

---

## Approach

The notebook is organized as a progression:

1. Setup and theme helpers
2. Beginner plots for distributions, counts, summaries, scatter, and line charts
3. Intermediate customization with hue, style, size, facets, palettes, and axes control
4. Advanced patterns such as pairplots, jointplots, regression helpers, ECDFs, hexbin density, and masked heatmaps
5. A compact Titanic EDA mini-pipeline
6. Best-practice notes and a final cheat sheet

---

## Key decisions

- **One notebook:** easier to read, run, and share on Kaggle/GitHub
- **Short cells:** each visual pattern is easy to copy and adapt
- **Small datasets:** fast execution and lower cognitive load
- **Version-aware code:** helper logic handles Seaborn `ci` vs `errorbar` differences
- **EDA-first framing:** the goal is visual understanding, not model training

---

## Practical value

This notebook can be used as:

- a learning reference for Seaborn
- a quick visual EDA checklist
- a reusable source of plotting snippets
- a portfolio artifact showing clean exploratory analysis structure

---

## Publishing notes

The notebook uses `sns.load_dataset(...)`, so internet access should be enabled when running from scratch.

For GitHub, the notebook is kept at the repository root for easy preview. For Kaggle, the same notebook can be uploaded and run directly.
