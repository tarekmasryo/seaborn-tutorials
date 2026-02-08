# 🧠 Case Study — Seaborn Beginner-to-Pro (EDA Reference)

## Problem
Build a practical, reusable reference for **Exploratory Data Analysis (EDA)** with Seaborn that:
- teaches plot selection (what to use, when)
- shows clean, copy-pasteable patterns
- stays readable as a single notebook

---

## Data
- **Source:** Seaborn built-in sample datasets via `sns.load_dataset()`
- **Examples:** `tips`, `penguins`, `flights`, `iris`, `titanic`
- **Note:** `sns.load_dataset()` may require internet on first run (Seaborn dataset download).

---

## Approach
- **Setup first:** consistent theme helpers + deterministic seed
- **Progression:** beginner → intermediate customization → advanced patterns
- **Patterns:** FacetGrid, pairplot/jointplot, regression fits, ECDF, hexbin, correlation heatmap
- **Mini-pipeline:** compact Titanic EDA workflow (missingness + numeric/categorical relationships)

---

## Results
- A single notebook that acts as a **visual EDA playbook**
- Reusable helper functions for:
  - theming
  - quick dataframe overview
  - plot templates with safe version handling (Seaborn 0.11 vs 0.12+)

---

## Decisions & Takeaways
- Keep everything in **one notebook** to reduce friction for readers.
- Prefer **short cells** and “one idea per plot” examples.
- Include version guards where Seaborn API differs (e.g., `ci` vs `errorbar`).

---

## Next Steps
- Add an optional section for loading a local CSV from `data/raw/` using `repo_utils/pathing.py`.
- Export a small gallery of plots into `artifacts/` for quick preview in the README.
