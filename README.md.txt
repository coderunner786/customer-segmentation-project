# Customer Segmentation & Spending Prediction 📊

This project was developed as part of the **BITS / Masai School Data Analytics** curriculum. It demonstrates a complete end-to-end machine learning pipeline, moving from raw transactional data to actionable business strategy.

## 🚀 Project Overview
The project is divided into two distinct phases to provide a 360-degree view of customer behavior.

### Phase 1: Customer Segmentation (Unsupervised Learning)
Using **K-Means Clustering**, I identified optimal customer segments by analyzing the **Elbow Curve** and **Silhouette Scores**.

* **Segment 1: High-Value Loyals** – High frequency and high spending.
    * *Strategy:* Premium loyalty programs to maximize lifetime value.
* **Segment 2: Value Seekers** – High frequency but low average order value.
    * *Strategy:* "Bundle" offers or "BOGO" to increase basket size.
* **Segment 3: At-Risk Shoppers** – Long periods since last purchase.
    * *Strategy:* Re-engagement email campaigns with targeted discounts.

### Phase 2: Spending Prediction (Supervised Learning)
I implemented a **Random Forest Regressor** to predict future spending behavior.

**Model Performance Metrics:**
* **R-Squared ($R^2$):** [Insert your score, e.g., 0.82] – This indicates the model explains a high percentage of the variance in customer spending.
* **Key Feature Importance:** The analysis revealed that **'Tenure with Company'** and **'Previous Month Spend'** were the strongest predictors of future behavior.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, GitHub