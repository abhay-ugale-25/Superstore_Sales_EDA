# 📊 Superstore Sales Data Analysis

A **data-driven analysis** of global superstore sales using Python. The project explores sales, profits, top products, customer segments, and regional performance, ending with **business recommendations** for decision-making.

---

## 📁 Dataset

* **Source:** [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
* **Description:** Historical sales data including customer orders, shipping details, profits, product categories, and regional sales.

---

## 🛠️ Tools & Libraries

* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Notebook:** Jupyter

---

## 📌 Analysis Workflow

### 1. Data Preparation

* Loaded dataset and checked for missing values
* Converted `Order Date` and `Ship Date` columns to datetime
* Created `year-month` feature for trend analysis

### 2. Sales & Profit Overview

* **Total Sales:** \$2,297,200.86
* **Total Profit:** \$286,397.02

### 3. Monthly Sales Trend

* Sales consistently peak in **Q4 (year-end)**
* Slight upward trend across 4 years

### 4. Top Products

* **Canon imageCLASS 2200 Advanced Copier** → > \$60K sales (largest single contributor)
* Big gap between #1 and other products

### 5. Regional Analysis

* **West & East:** Top-performing regions (> \$650K each)
* **Central & South:** Underperforming, need promotional focus

### 6. Additional Insights

* **Category Analysis:** Technology leads sales among product categories
* **Customer Segments:** Corporate and Consumer segments drive most revenue
* **Profit vs Sales:** Some high-sales products generate low profit (pricing issue)

### 7. Business Recommendations

* **Stock & Marketing:** Prepare inventory ahead of Q4 peak
* **Focus Products:** Promote top 5 products with targeted marketing
* **Regional Strategy:** Expand marketing in Central & South regions
* **Customer Programs:** Launch loyalty schemes for Corporate & Consumer buyers
* **Profit Optimization:** Revisit discounts/pricing for low-profit high-sales products

---

## 🔧 How to Run

1. Clone the repository
2. Install required libraries (`pip install -r requirements.txt`)
3. Run the Jupyter Notebook `notebook.ipynb`

---

## 📚 Conclusion

This project demonstrates how **data analysis + visualization** can uncover actionable insights: seasonal sales patterns, product profitability, and regional strategies. It is an ideal example of **business-focused data storytelling** using Python.
