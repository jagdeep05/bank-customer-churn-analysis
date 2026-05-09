# Bank Customer Churn Analysis
**Author:** Jagdeep Singh — Data Analyst  
**Tools:** Python (Pandas, Matplotlib, Seaborn) · SQL (SQLite)  
**Dataset:** 10,000 bank customer records  

---

## Objective
Identify which customers are likely to leave the bank (churn), uncover the key risk factors across geography, age, balance, and product usage, and deliver data-driven business recommendations to improve customer retention.

---

## Tools & Technologies
| Tool | Purpose |
|---|---|
| SQL (SQLite) | Data extraction, segmentation, aggregation |
| Python — Pandas | Data cleaning, preprocessing, feature engineering |
| Python — Matplotlib | Data visualisation, chart creation |
| Python — Seaborn | Correlation heatmap, statistical plots |
| Jupyter Notebook | End-to-end project documentation |

---

## Dataset
- **Size:** 10,000 customer records
- **Source:** Kaggle — Bank Customer Churn Prediction
- **Key columns:** CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited (1 = churned)

---

## Project Structure
```
bank-customer-churn-analysis/
│
├── Bank_Customer_Churn_Analysis.ipynb   ← Main Jupyter notebook
├── bank_churn.csv                       ← Dataset
├── chart1_geo_gender.png                ← Churn by geography & gender
├── chart2_age_balance.png               ← Churn by age group & balance
├── chart3_products_activity.png         ← Churn by products & activity
├── chart4_correlation.png               ← Correlation heatmap
├── chart5_top_segments.png              ← Top 10 highest churn segments
├── dashboard_summary.png                ← Full summary dashboard
└── README.md
```

---

## Key Findings

| # | Finding | Metric |
|---|---|---|
| 1 | Germany has the highest churn rate | Significantly above France and Spain |
| 2 | Customers aged 46–60 churn the most | Highest churn rate across all age bands |
| 3 | Customers with 3–4 products churn far more | Churn spikes sharply at 3+ products |
| 4 | Inactive members churn significantly more | ~10%+ higher than active members |
| 5 | Female customers churn more than male | Notable gender gap in churn rate |

---

## Business Recommendations

1. **Germany retention campaign** — Personalised offers, loyalty rewards, and proactive outreach for Germany customers
2. **Senior customer programme** — Higher interest savings, priority service, and retirement planning for 46–60 age group
3. **Product simplification** — Review bundling strategy for customers holding 3–4 products to reduce friction
4. **Re-engagement drive** — Push notifications, cashback incentives for inactive members
5. **Gender-focused feedback** — Survey female customers to identify pain points and improve service experience

---

## How to Run
```bash
# 1. Clone the repository
git clone https://github.com/your-username/bank-customer-churn-analysis.git
cd bank-customer-churn-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch Jupyter Notebook
jupyter notebook Bank_Customer_Churn_Analysis.ipynb

# 4. Run all cells (Kernel → Restart & Run All)
```

---

## Resume Bullets (ATS-Optimised)
> Conducted end-to-end churn analysis on 10,000+ bank customer records using SQL and Python (Pandas, Matplotlib, Seaborn), identifying top 3 churn risk segments across geography, age group, and balance tier.

> Wrote complex SQL queries to segment customers by churn status across 5 dimensions — geography, gender, age band, balance, and product count — uncovering key behavioural patterns in churned vs retained customers.

> Delivered 5 data-driven business recommendations with supporting visualisations, identifying that customers aged 46–60 in Germany had the highest churn rate — enabling targeted retention strategy for the highest-risk segments.

---

*Connect with me on [LinkedIn](https://linkedin.com/in/jagdeep-singh-475b12259)*
