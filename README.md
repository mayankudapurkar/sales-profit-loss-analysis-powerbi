# 📊 Sales Profit & Loss Analysis (Power BI Dashboard)

This project provides a Power BI dashboard for analyzing sales transactions with a focus on **profit and loss**, using a noisy, semi-realistic dataset.

## 📁 Files Included
- `Sales_Profit_Loss_Analysis.pbix`: Power BI dashboard file with visualizations.
- `README.md`: Project description and instructions.

---

## 📌 Key Features of the Dashboard

- ✅ Profit vs Loss breakdown by **region**, **product**, and **category**
- 📅 Trend analysis over time
- 📦 Product-level performance
- 📈 KPIs: Total Profit, Total Loss.

---

## 🔍 Dataset Description

The dataset contains 500+ rows and the following columns:

| Column         | Description |
|----------------|-------------|
| `Date`         | Order date |
| `Order_ID`     | Unique identifier |
| `Region`       | Geographic area (may include typos/noise) |
| `Product`      | Product sold |
| `Category`     | Product category |
| `Sub-Category` | Product sub-category |
| `Quantity`     | Units sold |
| `Unit_Price`   | Sale price per unit |
| `Cost_Price`   | Cost per unit |
| `Revenue`      | `Unit_Price × Quantity` |
| `Cost`         | `Cost_Price × Quantity` |
| `Profit`       | `Revenue - Cost` |
| `Profit/Loss`  | Profitability label |

---

## 📊 Visuals Used in Power BI

- Pie Chart: Profit vs Loss distribution
- Clustered Bar Chart:Sum of Profit by sub-category
- Line Chart: Monthly profit trend
- KPI Cards: Total Profit, Loss by Category

---

## 🔧 Tools Used

- Power BI Desktop
- GitHub (for versioning and sharing)

---

## 📂 How to Use

1. Clone or download the repo.
2. Open the `.pbix` file in Power BI Desktop.
3. Replace the data source if needed (use included `CSV` file).
4. Explore and customize visuals.


