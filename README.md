# Customer Business Risk Radar

##  Project Overview
The **Customer Business Risk Radar** is a customer-level analytics project designed to identify **business risk proactively** using behavioral, revenue, conversion, and trust-related signals.  
Instead of relying on lagging indicators such as churn or revenue loss, this project focuses on **early risk identification** to support better business decisions.

##  Business Problem
Most businesses realize customer risk only after revenue drops or customers churn.  
This project addresses a more actionable question:

 **Which customers currently pose business risk, and what factors are driving that risk?**

By answering this, businesses can take **targeted and data-driven actions**.

## Analytical Approach

### 1️ Risk Dimensions
Customer risk is modeled using four key dimensions:

- **Engagement Risk**  
  Low purchase frequency, fewer sessions, shorter session duration, and reduced interaction.

- **Revenue Risk**  
  Low total spend and low average order value.

- **Conversion Risk**  
  High cart abandonment and weak purchase intent.

- **Trust Risk**  
  High return rates and low campaign responsiveness.

### 2️ Risk Scoring Framework
- All features were normalized to a **0–100 scale**
- Higher values indicate **higher business risk**
- A weighted composite score was calculated as:

Customer Risk Score =
0.30 × Engagement Risk
0.30 × Revenue Risk
0.25 × Conversion Risk
0.15 × Trust Risk


Customers were classified into:
- **Low Risk**
- **Medium Risk**
- **High Risk**
  
##  Dataset
The project uses an **e-commerce customer segmentation dataset** containing:
- RFM metrics (Recency, Frequency, Monetary)
- Engagement behavior (sessions, clicks, pages viewed)
- Conversion indicators (cart abandonment, wishlist activity)
- Campaign response and return behavior

The dataset represents a **customer-level snapshot**, making it suitable for risk profiling and segmentation analysis.

##  Key Outputs
- Customer-level risk scores and risk categories
- Distribution of customers across risk levels
- Segment-wise risk analysis (Silver, Gold, Platinum, etc.)
- Identification of dominant risk drivers per segment.

## Dashboard
An executive-style **Power BI dashboard** was created to:
- Visualize overall customer risk distribution
- Highlight high-risk customers
- Compare risk across customer segments
- Explain *why* customers are risky using risk driver analysis

A dashboard screenshot is included in the `dashboard/` folder.

## Tools & Technologies
- **Python** (Pandas, NumPy)
- **Power BI**


## Business Impact
- Enables proactive identification of high-risk customers
- Supports targeted retention and engagement strategies
- Improves decision-making through explainable risk drivers
- Bridges the gap between analytics and business action

##  Future Enhancements
- Time-based customer risk tracking
- Automated risk alerts
- Integration with CRM or marketing systems
- Predictive risk modeling

##  Author
**Akshita Choudhary**  



