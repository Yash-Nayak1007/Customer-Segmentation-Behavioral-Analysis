# Customer-Segmentation-Behavioral-Analysis
This analysis evaluates transaction data across 500 customers to evaluate purchasing patterns, satisfaction levels, and revenue contributions. Total generated revenue stands at $46,265.43, with an Average Order Value (AOV) of $92.53 and an overall Discount Usage Rate of 42.0%.  
# 📊 Customer Segmentation & Behavioral Analysis

An end-to-end data analysis project exploring customer purchasing patterns, satisfaction metrics, and behavioral segmentation to drive targeted marketing and customer retention strategies.

---

## 📌 Project Overview
Understanding customer heterogeneity is critical for optimizing promotional spending and improving retention. This project analyzes transaction records for **500 customers** across various merchandise categories and purchase seasons, utilizing pre-segmented customer personas (**Champions**, **Loyal Customers**, **Potential Loyalists**, and **At Risk**) to derive actionable business insights.

---

## 💡 Key Business Findings

* **Champions (Cluster 1):** Highest value segment with an average spend of **$181.40** and exceptional satisfaction (**4.43 / 5.0** rating). They rely less on discounts (**33.3%** usage).
* **Loyal Customers (Cluster 2):** Represents the largest revenue base (**222 customers**, 44.4% of total). Strong spend (**$141.67** average), but average satisfaction sits at **2.70 / 5.0**, indicating a risk of churn if service/product issues aren't addressed.
* **Potential Loyalists (Cluster 3):** Mid-tier spenders (**$53.96** average) with decent ratings (**3.11 / 5.0**) and moderate discount usage (**44.4%**).
* **At Risk / Needs Attention (Cluster 4):** Low individual order value (**$27.04** average) and high discount dependency (**45.0%** usage).

---

## 📈 Cluster Profiles Breakdown

| Cluster Name | ID | Count | Avg Spend | Spend Range | Avg Rating | Discount Usage (%) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Champions** | 1 | 30 | $181.40 | $121.49 – $325.03 | 4.43 | 33.3% |
| **Loyal Customers** | 2 | 222 | $141.67 | $70.74 – $478.66 | 2.70 | 40.1% |
| **Potential Loyalists** | 3 | 99 | $53.96 | $40.37 – $69.88 | 3.11 | 44.4% |
| **At Risk / Needs Attention** | 4 | 149 | $27.04 | $15.35 – $39.04 | 2.98 | 45.0% |

---

## 🎯 Strategic Recommendations

1. **VIP Loyalty Program for Champions:** Offer early access to new product releases and exclusive perks rather than price discounts to preserve profit margins.
2. **Quality & Service Audit for Loyal Customers:** Because satisfaction in this core group is lower (2.70 average rating), send targeted feedback surveys to identify product quality or delivery pain points before churn occurs.
3. **Upselling Potential Loyalists:** Implement cross-selling recommendations in top categories (**Clothing** and **Footwear**) to lift average basket value above $70.
4. **Re-engagement Campaign for At-Risk Segment:** Use low-cost automated email sequences and limited-time bundle promotions rather than standalone discounts.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Data Visualization:** Power BI / Matplotlib

---

