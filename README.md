<div align="center">

<h1>High-Value Telecom Churn Prediction</h1>
<h3>Revenue Risk Modeling & Retention Optimization Framework</h3>

<p><strong>Author:</strong> Varshank Shukla</p>
<p><strong>Project Type:</strong> Predictive Analytics | Decision Intelligence</p>
<p><strong>Tools Used:</strong> Python (Pandas, NumPy, Scikit-Learn), PCA, XGBoost, SQL Logic, Matplotlib</p>

</div>

---

## 📌 Overview

This project develops a **revenue-focused churn prediction framework** for high-value telecom customers.

Unlike traditional churn models that stop at classification metrics (AUC, Accuracy), this framework reframes churn prediction as a **revenue risk management and decision optimization problem**.

The objective is not only to predict churn — but to:

- Quantify annual revenue exposure
- Optimize probability thresholds
- Simulate campaign cost vs revenue saved
- Recommend actionable retention strategies

---

## 🧠 Business Context

The telecom industry experiences annual churn rates of 15–25%.  
However, churn impact is not uniform — a small percentage of customers contribute disproportionately to total revenue.

Acquiring a new customer costs 5–10x more than retaining an existing one.

Therefore, the strategic priority is:

> Proactively identify high-value customers entering the behavioral “Action Phase” and intervene before full churn occurs.

---

## 🎯 Project Objectives

- Focus exclusively on top 30% revenue-generating customers
- Engineer churn definition using behavioral inactivity logic
- Eliminate data leakage from future-phase features
- Build predictive classification models
- Optimize recall to maximize revenue protection
- Simulate financial impact of retention campaigns

---

## 🏗 Methodology

### 1️⃣ High-Value Customer Segmentation
Customers ranked based on average recharge during Good Phase (Month 6 & 7).  
Top 30% selected for focused churn modeling.

---

### 2️⃣ Lifecycle Modeling

Telecom churn modeled using behavioral phases:

- **Good Phase** → Stable engagement
- **Action Phase** → Declining usage
- **Churn Phase** → Complete inactivity

Churn engineered based on inactivity signals during Action Phase.

---

### 3️⃣ Data Preparation

- Missing value treatment
- Removal of churn-phase features (to prevent leakage)
- Multicollinearity reduction
- PCA-based dimensionality reduction

---

### 4️⃣ Model Development

Supervised classification models applied:

- Logistic Regression
- Random Forest
- XGBoost

Evaluation Metrics:
- Recall (primary business metric)
- Precision
- ROC-AUC
- Confusion Matrix

---

### 5️⃣ Threshold Optimization

Default probability threshold (0.5) is suboptimal for revenue protection.

Threshold sensitivity analysis performed to:
- Increase recall
- Improve detection of revenue-risk customers
- Evaluate trade-off between false positives and missed churners

---

## 💰 Revenue Impact Analysis

Annual revenue exposure estimated as:

Annual Revenue at Risk =  
(Number of churners) × (Average Monthly Revenue) × 12

Further, a revenue simulation model was built incorporating:

- Acceptance rate of retention offers
- Campaign cost per targeted user
- Net gain calculation

This converts churn prediction into a financially measurable business strategy.

---

## 📊 Key Insights

- Behavioral decline in recharge and data usage strongly predicts churn.
- High-value churn represents significant annual revenue exposure.
- Optimized threshold selection materially improves net retention gain.
- Revenue-based evaluation provides stronger business alignment than accuracy-based evaluation.

---

## 🚀 Strategic Recommendations

1. Deploy recall-optimized churn model during Action Phase monitoring.
2. Implement tiered intervention strategy:
   - >0.7 probability → Immediate personalized retention
   - 0.4–0.7 probability → Targeted incentives
3. Continuously recalibrate threshold based on campaign cost & conversion rate.
4. Integrate churn scoring into CRM workflows.
5. Extend framework to cost-sensitive learning & uplift modeling.

---

## ⚠ Limitations & Future Scope

- No cost-sensitive learning applied
- No uplift modeling for incremental impact estimation
- No A/B testing validation
- No production deployment layer

Future enhancements may include:
- Uplift modeling
- Real-time churn scoring pipelines
- Customer lifetime value integration

---

## 📈 Business Impact

This framework transitions churn prediction from a statistical classification task to a **Revenue Intelligence System**, enabling:

- Proactive churn intervention
- Financially optimized threshold selection
- Data-driven retention strategy

---
## 📬 Connect With Me

If you're interested in discussing churn analytics, revenue optimization, or decision intelligence systems:

- LinkedIn: https://www.linkedin.com/in/varshank-s/
- Email: eklavyeshukla@gmail.com

