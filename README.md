# RFM Customer Segmentation (End-to-End)

A production-style, end-to-end **RFM (Recency–Frequency–Monetary) customer segmentation** project featuring:
- Quantile-based RFM scoring and interpretable segment labels (VIP, Loyal, Big Spenders, At Risk, etc.).
- Clean EDA and data preparation.
- **Machine learning classifiers** (Logistic Regression, Random Forest, Gradient Boosting, KNN, SVM) with **ROC/AUC** comparison.
- **Interactive Plotly dashboard** with KPI cards, segment distribution, R×F heatmap, and recency–frequency scatter.
- Reproducible environment via `requirements.txt`.

---

## 🧭 Project Structure

```
rfm-customer-segmentation/
├─ rfm_analysis_projectORIGNAL.ipynb          # Main notebook (end-to-end pipeline)
├─ rfm_for_bi.csv                      # Processed RFM table (ready for dashboards)
├─ rfm_plotly_dashboard_clean.html     # Polished Plotly dashboard (standalone HTML)
├─ rfm_models_roc_plotly.html          # Model ROC comparison (standalone HTML)
├─ rfm_plotly_dashboard.html           # (older variant) Plotly dashboard
├─ requirements.txt                    # Python dependencies
├─ LICENSE                             # Open-source license (MIT)
└─ assets/                             
```

> If HTML files don't render on GitHub, download and open locally in a browser.

---

## 🚀 Quickstart

```bash

# create environment (optional) and install
pip install -r requirements.txt

# run the notebook
jupyter notebook rfm_analysis_projectORIGNAL.ipynb
```

To view dashboards without running code, open:
- `rfm_plotly_dashboard_clean.html`
- `rfm_models_roc_plotly.html`

---

## 📊 Highlights

- **RFM Scoring**: quantile-based R, F, M scores with deterministic, explainable segment labels.
- **Interactive Visuals**: KPI cards, Segment treemap/bar, R×F heatmap, scatter sized by Monetary.
- **Modeling**: multiple classifiers evaluated with **ROC/AUC** and confusion matrix.
- **Clean Code**: modular, reproducible, and portfolio-ready.

---

## 🛠 Tech Stack

- Python, pandas, numpy
- scikit-learn (modeling)
- Plotly (interactive visualizations)
- Jupyter Notebook

---

## 📜 License

Released under the **MIT License** (see `LICENSE`).

---

## 🙌 Author

MURTAZA BAIG / Freelancer Alias  
Portfolio | Fiverr | Upwork | LinkedIn
