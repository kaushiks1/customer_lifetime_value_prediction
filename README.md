# Customer Lifetime Value Prediction

## Project Overview

This project predicts **future 12-month Customer Lifetime Value (CLV)** using realistic ecommerce, digital analytics, marketing, and customer engagement data.

It is designed as a professional **Marketing Analytics / Digital Analytics / Data Science** portfolio project.

---

## Business Problem

Marketing teams often spend the same amount on all customers, even though some customers are likely to generate significantly higher future value than others.

The key business question is:

> Which customers are likely to generate the highest future value over the next 12 months?

By predicting CLV, businesses can improve:

- Customer retention
- CRM personalization
- Marketing budget allocation
- Paid media audience strategy
- Discount efficiency
- Loyalty program targeting

---

## Dataset

The dataset is synthetic but designed to reflect realistic ecommerce customer behaviour.

### Files

```text
data/customer_clv_dataset.csv
data/transactions.csv
data/data_dictionary.csv
```

### Dataset Size

- 8,000 customers
- Transaction-level order history
- Acquisition channel information
- Web analytics behaviour
- Customer engagement metrics
- Future 12-month CLV target variable

---

## Features Used

The model uses features such as:

- Tenure
- Recency
- Purchase frequency
- Average order value
- Historical revenue
- Gross margin rate
- Discount usage rate
- Return rate
- Website sessions
- Product views
- Cart additions
- Email open rate
- Support tickets
- Churn risk score
- Country
- Device
- Acquisition channel

---

## Modelling Approach

A **Random Forest Regressor** is used to predict future 12-month CLV.

The workflow includes:

1. Data loading
2. Exploratory data analysis
3. Feature selection
4. Categorical encoding
5. Train/test split
6. Model training
7. Model evaluation
8. CLV prediction
9. Customer tiering
10. Business strategy recommendations

---

## Folder Structure

```text
customer_lifetime_value_prediction/
│
├── data/
│   ├── customer_clv_dataset.csv
│   ├── transactions.csv
│   └── data_dictionary.csv
│
├── notebooks/
│   └── customer_lifetime_value_prediction.ipynb
│
├── reports/
│   ├── customer_clv_predictions.csv
│   ├── clv_tier_summary.csv
│   ├── feature_importance.csv
│   ├── model_performance.csv
│   └── figures/
│       ├── actual_vs_predicted_clv.png
│       ├── clv_by_acquisition_channel.png
│       ├── feature_importance.png
│       └── predicted_clv_by_tier.png
│
├── docs/
│   └── project_summary.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Key Outputs

| Output | Description |
|---|---|
| `customer_clv_predictions.csv` | Customer-level predicted CLV and CLV tier |
| `clv_tier_summary.csv` | Summary of behaviour and value by CLV tier |
| `feature_importance.csv` | Most important CLV prediction drivers |
| `model_performance.csv` | MAE, RMSE, and R² model metrics |
| `actual_vs_predicted_clv.png` | Model prediction performance chart |
| `feature_importance.png` | Top drivers of future CLV |
| `predicted_clv_by_tier.png` | Average predicted CLV by tier |
| `clv_by_acquisition_channel.png` | Average predicted CLV by acquisition channel |

---

## Business Recommendations

### Top CLV Customers

These customers are predicted to deliver the highest future value.

Recommended actions:

- VIP loyalty rewards
- Early product access
- Premium product recommendations
- Personalized CRM journeys
- Retention-focused campaigns

### High CLV Customers

These customers show strong growth and repeat-purchase potential.

Recommended actions:

- Cross-sell campaigns
- Product bundles
- Personalized recommendations
- Membership incentives

### Medium CLV Customers

These customers have moderate future value and can be grown with targeted engagement.

Recommended actions:

- Nurture journeys
- Basket recovery campaigns
- Personalized content
- Targeted offers

### Low CLV Customers

These customers have lower predicted value or higher churn risk.

Recommended actions:

- Low-cost automated campaigns
- Suppress expensive paid retargeting
- Avoid unnecessary discounts
- Test win-back campaigns only when margin-positive

---

## Marketing Analytics Use Cases

- Prioritize CRM campaigns
- Improve customer retention
- Build high-CLV lookalike audiences
- Optimize acquisition channels by customer value
- Reduce wasted discounting
- Improve lifecycle marketing strategy

---

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Random Forest Regressor
- Customer Analytics
- Marketing Analytics
- Predictive Modelling

---

## Author

Kaushik Somashekar  
Digital Analyst | Product Analyst | Data Analyst | Aspiring Data Scientist
