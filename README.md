# zepto-analytics-pipeline
# 🛒 Zepto Analytics Pipeline

An end-to-end data analytics project on Zepto's grocery catalog data — SQL data exploration, Python data cleaning & EDA, and (upcoming) an interactive Tableau dashboard.

## 📌 About

Zepto is a quick-commerce grocery delivery platform. This project uses a snapshot of Zepto's product catalog to explore pricing, discounts, stock availability, and inventory logistics through SQL and Python, with insights ultimately visualized in a Tableau dashboard.

## 🗂️ Repository Structure

```
zepto-analytics-pipeline/
│
├── sql/
│   └── zepto_analysis.sql       # Schema, data quality checks, analytical queries
│
├── notebooks/
│   └── zepto_eda.ipynb          # Data cleaning + EDA
│
├── data/
│   └── zepto_v2.csv             # Raw dataset
│
└── README.md
```

## 🔍 Dataset

- **Rows:** 3,732 | **Columns:** 9 | **Categories:** 14
- Fields: category, name, mrp, discount %, available quantity, discounted selling price, weight (grams), out-of-stock flag, quantity

## 🧰 Tech Stack

- SQL (PostgreSQL)
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Tableau *(coming soon)*

## ✅ Progress

- [x] SQL schema creation & data quality checks
- [x] SQL analytical queries (revenue, discounts, stock, logistics)
- [ ] Python data cleaning
- [ ] Exploratory Data Analysis
- [ ] Tableau dashboard
- [ ] Final insights write-up

## 🚀 Setup

```bash
git clone https://github.com/<your-username>/zepto-analytics-pipeline.git
```

Run `sql/zepto_analysis.sql` against a PostgreSQL instance, then open `notebooks/zepto_eda.ipynb` in Jupyter or Google Colab.

---

*This project is a work in progress — README will be expanded as each stage is completed.*
