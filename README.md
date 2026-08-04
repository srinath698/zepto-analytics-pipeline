# 🛒 Zepto Analytics Pipeline

An end-to-end data analytics project analyzing Zepto grocery catalog data to uncover insights into **pricing, discounts, inventory availability, revenue potential, product weight, and stockout risk**.

The project follows a complete analytics workflow:

**SQL → Data Cleaning → Feature Engineering → EDA → Statistical Analysis → Visualization → Business Insights**

---

## 📌 About the Project

Zepto is a quick-commerce grocery delivery platform where product availability, pricing, discounts, and inventory levels directly influence customer experience and operational efficiency.

This project analyzes a snapshot of Zepto's product catalog to answer questions such as:

- Which categories have the highest revenue potential?
- Which categories have the highest stockout risk?
- How are products distributed across different price levels?
- Is there a relationship between MRP and discount percentage?
- Which products represent high-value inventory opportunities?
- Which categories contribute the most inventory weight?
- Where are potential pricing and margin opportunities?

The goal is not just to analyze the data, but to convert the analysis into **actionable business insights**.

---

## 🎯 Project Objectives

1. Clean and validate the raw product catalog.
2. Identify data quality issues and duplicate product names.
3. Engineer useful business features.
4. Analyze pricing and discount patterns.
5. Analyze inventory availability and stockout rates.
6. Estimate revenue potential from available inventory.
7. Study relationships between product attributes.
8. Visualize important business metrics.
9. Translate analytical findings into stakeholder-friendly insights.

---

## 📊 Dataset

The dataset contains a snapshot of Zepto's grocery product catalog.

### Dataset Overview

| Metric | Value |
|---|---:|
| Original rows | 3,732 |
| Columns | 9 |
| Categories | 14 |
| Missing values | 0 |
| Rows removed | 1 |
| Final rows analyzed | 3,731 |
| Duplicate product names | 2,051 |

### Columns

| Column | Description |
|---|---|
| `category` | Product category |
| `name` | Product/SKU name |
| `mrp` | Maximum Retail Price |
| `discount_pct` | Discount percentage |
| `available_qty` | Available inventory quantity |
| `discounted_selling_price` | Selling price after discount |
| `weight_gms` | Product weight in grams |
| `out_of_stock` | Whether the product is out of stock |
| `quantity` | Product quantity |

---

## 🧰 Tech Stack

### Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Database & SQL
- PostgreSQL
- SQL

### Dashboarding
- Tableau Public *(dashboard exploration / development)*

### Documentation
- GitHub
- Jupyter Notebook

---

# 🔄 Analytics Workflow

```text
Raw Zepto Dataset
       ↓
Data Quality Checks
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Matplotlib + Seaborn Visualizations
       ↓
Business Insights
       ↓
Stakeholder Flashcards
       ↓
Tableau Dashboard Exploration# 🛒 Zepto Analytics Pipeline

An end-to-end data analytics project analyzing Zepto grocery catalog data to uncover insights into **pricing, discounts, inventory availability, revenue potential, product weight, and stockout risk**.

The project follows a complete analytics workflow:

**SQL → Data Cleaning → Feature Engineering → EDA → Statistical Analysis → Visualization → Business Insights**

---

## 📌 About the Project

Zepto is a quick-commerce grocery delivery platform where product availability, pricing, discounts, and inventory levels directly influence customer experience and operational efficiency.

This project analyzes a snapshot of Zepto's product catalog to answer questions such as:

- Which categories have the highest revenue potential?
- Which categories have the highest stockout risk?
- How are products distributed across different price levels?
- Is there a relationship between MRP and discount percentage?
- Which products represent high-value inventory opportunities?
- Which categories contribute the most inventory weight?
- Where are potential pricing and margin opportunities?

The goal is not just to analyze the data, but to convert the analysis into **actionable business insights**.

---

## 🎯 Project Objectives

1. Clean and validate the raw product catalog.
2. Identify data quality issues and duplicate product names.
3. Engineer useful business features.
4. Analyze pricing and discount patterns.
5. Analyze inventory availability and stockout rates.
6. Estimate revenue potential from available inventory.
7. Study relationships between product attributes.
8. Visualize important business metrics.
9. Translate analytical findings into stakeholder-friendly insights.

---

## 📊 Dataset

The dataset contains a snapshot of Zepto's grocery product catalog.

### Dataset Overview

| Metric | Value |
|---|---:|
| Original rows | 3,732 |
| Columns | 9 |
| Categories | 14 |
| Missing values | 0 |
| Rows removed | 1 |
| Final rows analyzed | 3,731 |
| Duplicate product names | 2,051 |

### Columns

| Column | Description |
|---|---|
| `category` | Product category |
| `name` | Product/SKU name |
| `mrp` | Maximum Retail Price |
| `discount_pct` | Discount percentage |
| `available_qty` | Available inventory quantity |
| `discounted_selling_price` | Selling price after discount |
| `weight_gms` | Product weight in grams |
| `out_of_stock` | Whether the product is out of stock |
| `quantity` | Product quantity |

---

## 🧰 Tech Stack

### Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Database & SQL
- PostgreSQL
- SQL

### Dashboarding
- Tableau Public *(dashboard exploration / development)*

### Documentation
- GitHub
- Jupyter Notebook

---

# 🔄 Analytics Workflow

```text
Raw Zepto Dataset
       ↓
Data Quality Checks
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Matplotlib + Seaborn Visualizations
       ↓
Business Insights
       ↓
Stakeholder Flashcards
       ↓
Tableau Dashboard Exploration
