# Customer Churn Prediction & Retention Recommendation System

A business-focused ML solution to identify high-risk customers and increase revenue retention.

---

## Business Problem

Customer churn is a *major issue* for subscription-based businesses. Losing customers impacts revenue directly.  

This project helps businesses:  

- Identify *high-risk customers* before they leave  
- Take *proactive retention actions*  
- Save *thousands of pounds per month*  
- Make *data-driven decisions* without manual analysis  

*Goal:* Reduce churn, increase revenue, and improve customer loyalty.

---

## Dataset Used

*Dataset:* Telco Customer Churn Dataset  

*Source:* Public dataset from Kaggle / IBM sample datasets  

*Description:*

| Column               | Description                                           |
|---------------------|-------------------------------------------------------|
| customerID        | Unique ID of the customer                             |
| gender            | Customer gender                                       |
| SeniorCitizen     | 1 if senior citizen, 0 otherwise                     |
| tenure            | Number of months customer has stayed                  |
| MonthlyCharges    | Monthly subscription charges                           |
| TotalCharges      | Total charges                                        |
| Churn             | Target variable: Yes = churn, No = retained          |
| risk_category     | Predicted churn risk (High / Medium / Low)           |
| churn_probability | Predicted probability of churn                        |

*Why this dataset?*  
It represents *real business scenarios, making the model **directly applicable* to subscription services.

---

## Solution Overview

The solution includes:

1. *Data Cleaning & Feature Engineering*  
   - Handle missing values (TotalCharges)  
   - Drop unnecessary columns (customerID)  
   - Encode categorical variables  

2. *ML Model: Logistic Regression*  
   - Simple, interpretable, business-friendly  
   - Focus on *recall* to identify as many potential churners as possible  

3. *Retention Recommendation Logic*  
   - High Risk: Offer discount or personal call  
   - Medium Risk: Loyalty program / offer  
   - Low Risk: Upsell opportunities  

4. *Output:*  
   - churn_predictions.csv — ready for CRM integration  
   - Excel-based overview of churn predictions for business review  

---

## Business Impact (ROI)

Example scenario:

- *Total customers:* 1,000  
- *Average monthly revenue per customer:* £50  
- *Retain 20 high-risk customers per month* → *£1,000 saved per month* → *£12,000 per year*  

> Small improvements in churn retention *translate to significant revenue savings*, making this solution immediately valuable to any subscription business.

---

## Churn Overview (Excel Screenshots)

The Excel file shows predicted *risk categories* and recommended retention actions.  
Business users can *filter by risk* to prioritize actions.

### Screenshots

1. *Full Overview (All Customers)*

<img width="957" height="370" alt="1" src="https://github.com/user-attachments/assets/245551ad-9adc-44c9-8a60-3caf90be272a" />


2. *High Risk Customers*

<img width="261" height="345" alt="2" src="https://github.com/user-attachments/assets/5e704791-7efe-42a0-b067-c8fbb47bad7c" />


> Businesses can use this Excel overview to *quickly identify and act on high-risk customers*.

---

## How Businesses Can Use This

1. Load churn_predictions.csv into your CRM or Excel  
2. Filter customers by risk_category  
3. Apply recommended retention actions:
   - High: Direct personal contact or special offers  
   - Medium: Loyalty rewards  
   - Low: Upsell products or services  
4. Track impact monthly and *reduce churn systematically*  

---

## Key Features & Advantages

| Feature                          | Benefit                                                                 |
|---------------------------------|-------------------------------------------------------------------------|
| Predicts churn probability       | Businesses know *who is likely to leave*                               |
| Risk categorization              | Focus efforts on *high-impact customers*                               |
| Actionable retention recommendations | Turn predictions into *revenue-saving actions*                        |
| CSV export / Excel overview      | *Easy to implement*, no technical expertise needed                     |
| Business-oriented ML             | Interpretable and explainable, *not just fancy models*                 |

---

## Technology Stack

- *Python* – Data processing & modeling  
- *Pandas* – Data manipulation  
- *Scikit-learn* – Logistic regression modeling  
- *Excel / CSV* – Business-friendly review of churn predictions  

---

## Why This Project is Client-Ready

- Focused on *business outcome, not just accuracy*  
- *Decision-making tool* for retention teams  
- Ready to *generate immediate ROI*  
- Fully *documented and portfolio-ready*  

> This project demonstrates *practical ML applied to real business problems, making you stand out as someone who delivers **value, not just code*.

---

## Next Steps for Businesses / Clients

- Integrate the CSV output into your CRM system or Excel  
- Apply retention recommendations to high-risk customers  
- Monitor reduction in churn monthly  
- Optionally, expand to *interactive dashboards* in the future  

---

## Contact / Hire Me

I help businesses *turn ML insights into actionable revenue-saving strategies*.  
- Reduce churn, retain revenue, improve customer loyalty  
- Fully remote and quick delivery  
- Ready-to-implement, portfolio-tested solution  

> *Get in touch* to implement this solution for your business today!
