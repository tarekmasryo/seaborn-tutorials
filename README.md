# 📊 Seaborn — Beginner-to-Pro (EDA Reference) 🎯

A practical notebook for **Exploratory Data Analysis (EDA)** with Seaborn: beginner basics → customization → advanced patterns.

---

## ✅ What’s inside

- 🧭 Clean, modular examples you can reuse in real projects  
- 🧱 A compact EDA mini-pipeline (Titanic)  
- 🧩 Version-safe snippets (Seaborn 0.11 vs 0.12+)  
- 📁 Lightweight repo layout (`data/raw`, `artifacts`) for optional extensions

---

## 🖼️ Example plots

- Distribution with histogram + KDE
- FacetGrid of penguins by island × sex
- Pairplot of Iris dataset
- Hexbin for dense scatter clouds
- Correlation heatmap with upper-triangle mask

---

## 📂 Data

This notebook uses **Seaborn built-in sample datasets**:
- `tips`, `penguins`, `flights`, `iris`, `titanic`

Note: `sns.load_dataset()` may need internet on first run (dataset download).  
If you want to run fully offline, place your own CSV under `data/raw/`.

---

## 📁 Repo layout

```text
.
├── seaborn-beginner-to-pro-clean-eda-guide.ipynb
├── data/
│   └── raw/               # optional local datasets (kept out of git)
├── artifacts/             # optional exported figures / outputs
├── repo_utils/
│   └── pathing.py         # local + Kaggle path helpers (optional)
├── CASE_STUDY.md
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Run locally

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

pip install -r requirements.txt
```

Open the notebook and run top-to-bottom in:
- Jupyter / JupyterLab
- VS Code notebooks

---

## 🧾 Case Study

See: **CASE_STUDY.md** (project story + key decisions, without repeated run steps).
