
# IBM Customer Churn Analytics & Retention Strategy

### End-to-End Data Analytics | SQL | Python | Machine Learning | Power BI

An end-to-end customer churn analytics project built using SQL, Python, Machine Learning, and Power BI to identify customer churn patterns, predict high-risk customers, analyze revenue at risk, and develop data-driven customer retention strategies.

The objective is to transform customer data into actionable business intelligence that helps telecom businesses reduce customer attrition, protect recurring revenue, and improve Customer Lifetime Value (CLTV).

---

## 1. Business Problem

Customer churn is one of the major challenges faced by subscription-based telecom businesses.

When customers discontinue their services, businesses experience:

- Revenue loss due to customer cancellations.
- Increased customer acquisition costs.
- Reduced Customer Lifetime Value (CLTV).
- Difficulty identifying customers likely to leave.
- Ineffective customer retention campaigns.
- Loss of high-value and long-term customers.

### Key Business Questions

1. What percentage of customers are leaving the business?
2. Which customer segments have the highest churn rate?
3. Which contracts and payment methods are associated with higher churn?
4. How much revenue is at risk due to customer attrition?
5. Which high-value customers are likely to churn?
6. How can businesses identify churn before customers leave?
7. What retention strategies can improve customer loyalty?

**Business Objective:** Develop a data-driven churn intelligence solution to identify customer attrition patterns, predict churn risk, and help businesses make proactive retention decisions.

---

## 2. Business Solution

This project develops an integrated Customer Churn Analytics and Retention Intelligence System.

| Analytical Component | Business Solution |
|---|---|
| SQL Analysis | Identify churn patterns and customer segments |
| Python EDA | Discover customer behaviour and churn drivers |
| Customer Segmentation | Categorize customers based on churn risk |
| Machine Learning | Predict customers likely to churn |
| Revenue at Risk Analysis | Identify potential revenue loss |
| High-Value Customer Analysis | Prioritize customers with high CLTV |
| Power BI Dashboard | Monitor KPIs and support business decisions |

### Business Value

The solution helps businesses move from reactive customer management to proactive customer retention by identifying at-risk customers before they leave.

---

## 3. Tools & Technologies

| Category | Technologies |
|---|---|
| Data Analysis | Python, Pandas, NumPy |
| Database | MySQL |
| Data Cleaning | SQL, Python |
| Machine Learning | Scikit-learn |
| ML Algorithms | Logistic Regression, Random Forest |
| Feature Engineering | Customer Behaviour Features |
| Data Visualization | Matplotlib, Seaborn |
| Business Intelligence | Microsoft Power BI |
| Dashboard Design | KPI Cards, Slicers, Interactive Charts |

---

## 4. Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographics, account information, subscribed services, contract details, payment methods, monthly charges, total charges, and customer churn status.

- Total Customer Records: 7,043
- Customer Information: Demographics and Account Details
- Financial Information: Monthly and Total Charges
- Customer Behaviour: Tenure, Contract and Services
- Target Variable: Churn

---

## 5. Project Workflow

```text
IBM Telco Customer Churn Dataset
              |
              v
       Data Collection
              |
              v
      Data Cleaning
       SQL + Python
              |
              v
 Exploratory Data Analysis
              |
              v
     Feature Engineering
              |
              v
   Customer Segmentation
              |
              v
   Machine Learning Model
              |
              v
     Churn Prediction
              |
              v
    Revenue Risk Analysis
              |
              v
     Power BI Dashboard
              |
              v
 Business Insights & Retention Strategy
```

---

## 6. Business KPI Overview

The analysis covers 7,043 telecom customers and highlights the following business performance indicators.

| KPI | Actual Result | Business Meaning |
|---|---:|---|
| Total Customers | 7,043 | Overall customer base |
| Total Revenue | 456K | Revenue represented in the dashboard |
| Retained Customers | 5,174 | Customers who stayed |
| Churn Rate | 26.5% | Percentage of customers lost |
| Retention Rate | 73.5% | Percentage of customers retained |
| Average Tenure | 32.37 Months | Average customer relationship duration |

### Customer Retention vs Churn

| Customer Status | Percentage |
|---|---:|
| Retained Customers | 73.5% |
| Churned Customers | 26.5% |

**Business Interpretation:**

Approximately 1 in every 4 customers leaves the business. This represents a significant customer retention challenge and highlights the importance of early churn detection.

---

## 7. Power BI Dashboard Overview

### Dashboard Page 1 — Customer Churn Overview

This dashboard provides an overall view of customer retention, churn distribution, and customer behaviour.

**Key KPIs:**
- Total Customers: 7,043
- Total Revenue: 456K
- Retained Customers: 5,174
- Churn Rate: 26.5%
- Average Tenure: 32.37 Months

**Visualizations:**
- Customer Churn by Internet Service.
- Churn Trend by Customer Tenure.
- Churn by Payment Method.
- Churn by Contract Type.
- Overall Customer Retention Analysis.

### Dashboard Preview

![Customer Churn Overview Dashboard](IBM%20Customer%20Churn%20Analysis%20Page-1.png)

### Dashboard Page 2 — High-Value Customer Churn Analysis

This dashboard focuses on identifying high-value customers who are at risk of leaving and understanding their potential revenue impact.

**Key Analysis:**
- Churn Score by Customer Lifetime Value (CLTV).
- Revenue at Risk Analysis.
- Customer Value vs Tenure.
- Churn Risk by Internet Service.
- Contract-Based Churn Analysis.

### Dashboard Preview

![High Value Customer Churn Dashboard](IBM%20High%20Value%20Customer%20Churn%20Page-2.png)

---

## 8. Key Business Insights

The analysis revealed several important customer behaviour patterns.

| Business Insight | Analytical Finding | Business Implication |
|---|---|---|
| Overall Churn | 26.5% | Significant customer attrition |
| Retention Rate | 73.5% | Opportunity to improve retention |
| Contract Type | Month-to-month customers contribute approximately 45% of churn | Encourage long-term contracts |
| Customer Tenure | Customers with less than 6 months of tenure show higher churn risk | Improve new customer onboarding |
| Payment Method | Electronic check users show approximately 25% higher churn than auto-pay users | Promote automatic payments |
| Internet Service | Fiber optic customers show approximately 35% churn | Investigate service quality and pricing |
| Monthly Charges | Higher monthly charges are associated with 30–40% higher churn | Introduce competitive pricing and value-based offers |
| Customer Value | High-CLTV customers represent an important revenue retention priority | Protect high-value revenue |

*Percentage comparisons reflect the reported analysis and should be interpreted according to the relevant segment definitions and denominators.*

### Insight 1 — Contract-Based Churn

Month-to-month customers contribute approximately 45% of churn.

**Business Opportunity:** Encourage customers to switch to annual or long-term contracts through loyalty benefits and contract upgrade offers.

![Churn by Contract](u_Churn%20by%20Contract.png)

### Insight 2 — Predicted Customer Behaviour

Machine Learning analysis helps identify customers likely to churn and customers expected to stay.

**Business Opportunity:** Use churn probability scores to prioritize retention campaigns.

![Predicted Customer Behaviour](x_Predicted%20Customer%20behaviour.png)

### Insight 3 — Top 10 Reasons Behind Customer Churn

Understanding the major churn reasons helps businesses identify operational and service-related improvement opportunities.

**Business Opportunity:** Develop targeted solutions based on the most significant customer dissatisfaction factors.

![Top 10 Reasons Behind Customer Churn](y_Top%2010%20Reason%20of%20Customer%20Churn.png)

### Insight 4 — Machine Learning Confusion Matrix

The confusion matrix evaluates the classification performance of the churn prediction model.

It helps identify:

- True Positive: Correctly predicted churn customers.
- True Negative: Correctly predicted retained customers.
- False Positive: Retained customers incorrectly predicted to churn.
- False Negative: Churn customers incorrectly predicted to stay.

**Business Opportunity:** Improve churn detection while balancing missed churners against unnecessary retention campaign costs.

![Machine Learning Confusion Matrix](z_Confusion_Matrix.png)

---

## 9. Machine Learning — Customer Churn Prediction

A supervised Machine Learning approach was implemented to predict customer churn behaviour.

### Algorithms Explored
- Logistic Regression
- Random Forest Classifier

### Features Used

| Feature | Business Relevance |
|---|---|
| Tenure | Measures customer relationship duration |
| Monthly Charges | Identifies pricing-related churn patterns |
| Contract | Evaluates contract commitment |
| Payment Method | Identifies payment-related behaviour |
| Internet Service | Evaluates service-related churn patterns |
| Total Charges | Represents accumulated customer spending |

### Model Output

- Churn Probability Score.
- Predicted Customer Behaviour.
- Customer Risk Classification.
- High-Value Customer Risk Identification.

The prediction output can support proactive customer retention by helping businesses focus on customers with higher churn probabilities.

---

## 10. Business Improvement Opportunities

Based on the analytical findings, the following opportunities can help telecom businesses improve retention and protect revenue.

| Business Challenge | Recommended Improvement | Expected Business Benefit |
|---|---|---|
| High Month-to-Month Churn | Offer annual contract incentives | Improve contract stability |
| High New Customer Churn | Strengthen first 90-day onboarding | Improve early retention |
| Electronic Check Churn | Promote automatic payment options | Improve payment convenience |
| High Fiber Optic Churn | Investigate network quality and service complaints | Improve customer satisfaction |
| High Monthly Charges | Introduce personalized pricing and bundled packages | Reduce price-related attrition |
| High-Value Customer Loss | Launch VIP retention and loyalty programs | Protect high-value revenue |
| Late Churn Identification | Implement predictive churn monitoring | Enable early intervention |
| Generic Retention Campaigns | Segment customers by churn probability | Improve campaign targeting |

### Priority Areas for Business Improvement

**1. New Customer Retention**

Customers in their first six months require special attention.

Action:
- Introduce welcome programs.
- Provide onboarding assistance.
- Monitor early complaints.
- Conduct follow-up communication.

**2. High-Value Customer Protection**

High-CLTV customers should receive priority retention attention.

Action:
- Introduce personalized loyalty benefits.
- Offer exclusive service packages.
- Monitor high-value customer churn scores.
- Provide proactive customer support.

**3. Contract Optimization**

Month-to-month customers represent a major churn opportunity.

Action:
- Offer discounts on long-term subscriptions.
- Introduce flexible annual plans.
- Reward contract renewals.

**4. Pricing & Service Improvement**

Higher monthly charges and fiber optic churn indicate areas requiring further investigation.

Action:
- Review pricing competitiveness.
- Monitor service complaints.
- Improve service reliability.
- Offer customized packages.

---

## 11. Proposed Business Improvement KPIs

The following are suggested future targets, not measured outcomes of the current project.

| Business KPI | Current Baseline | Proposed Target | Improvement Objective |
|---|---:|---:|---|
| Churn Rate | 26.5% | 21.5% | Reduce by 5 percentage points |
| Retention Rate | 73.5% | 78.5% | Increase by 5 percentage points |
| Early Customer Churn | Higher risk below 6 months | Reduce by 15% | Improve onboarding |
| High-Value Customer Retention | Requires monitoring | Improve by 10% | Protect valuable customers |
| Auto-Payment Adoption | Requires baseline measurement | Increase by 15% | Improve payment adoption |
| Retention Campaign Effectiveness | Requires baseline measurement | Improve by 10% | Optimize targeting |

### Potential Business Impact

If the business reduces churn from 26.5% to 21.5%, the improvement would represent:

- 5 percentage-point reduction in churn.
- Approximately 18.9% relative reduction in churn.
- Approximately 5 percentage-point increase in retention, assuming the same customer base and binary churn status.

These are proposed improvement scenarios, not results achieved or validated by the project.

---

## 12. Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Reduce Customer Churn:** Target high-risk customers with personalized retention campaigns.
2. **Improve Customer Onboarding:** Focus on customers during their first six months.
3. **Increase Long-Term Contracts:** Provide incentives for annual and long-term subscriptions.
4. **Protect High-Value Customers:** Prioritize high-CLTV customers with dedicated loyalty programs.
5. **Promote Auto-Payment:** Encourage convenient automatic payment methods.
6. **Improve Service Quality:** Investigate fiber optic customer dissatisfaction.
7. **Optimize Pricing:** Develop personalized packages based on customer spending behaviour.
8. **Use Predictive Analytics:** Monitor churn probability to identify customers requiring immediate attention.

---

## 13. Project Highlights

- End-to-End Customer Churn Analytics.
- Advanced SQL-Based Data Analysis.
- Python-Based Data Cleaning and EDA.
- Customer Behaviour Analysis.
- Machine Learning-Based Churn Prediction.
- Customer Risk Segmentation.
- Revenue at Risk Analysis.
- High-Value Customer Analysis.
- Interactive Power BI Dashboards.
- Business KPI Development.
- Data-Driven Retention Recommendations.

---

## 14. Skills Demonstrated

### Technical Skills
- SQL & MySQL
- Python
- Pandas & NumPy
- Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Machine Learning
- Scikit-learn
- Power BI
- Data Visualization

### Business & Analytical Skills
- Customer Churn Analysis
- Customer Segmentation
- Revenue Analysis
- KPI Development
- Customer Retention Strategy
- Business Intelligence
- Predictive Analytics
- Data Storytelling
- Business Problem Solving

---

## 15. Future Improvements

Potential enhancements to make the solution more useful in a real business environment:

- Deploy the churn prediction model as a real-time prediction API.
- Integrate automated customer risk alerts.
- Build customer-level retention recommendation systems.
- Implement customer lifetime value prediction.
- Track retention campaign performance.
- Integrate CRM data for customer-level action tracking.
- Monitor model performance and prediction drift.
- Conduct A/B testing to measure the actual impact of retention campaigns.

---

## 16. About Me

I am a BCA graduate and MCA student with a strong interest in Data Analytics, Data Science, and Machine Learning.

I enjoy transforming raw datasets into meaningful business insights using SQL, Python, Machine Learning, and Power BI.

My focus is on solving real-world business problems through data-driven analysis, predictive modelling, interactive dashboards, and actionable business recommendations.

**Areas of Interest:** Data Analyst | Data Scientist | Business Intelligence | Machine Learning

---

⭐ If you find this project useful, consider giving this repository a star!

