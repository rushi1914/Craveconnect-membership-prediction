# CraveConnect — Customer Membership Upgrade Prediction

## Problem Statement
Predict which food app users are likely to upgrade their membership tier, enabling targeted marketing.

## Dataset
1000+ synthetic food app customers with 18 features including demographics, spending behavior, cuisine preferences, and app engagement.

## Approach
EDA → Feature Engineering → ML Model → Propensity Scoring → Tier Bucketing (Cold / Warm / Hot / Very Hot)

## Key Features Used
- Annual_Income, Spending_Score, Purchase_Frequency
- App_Rating, Avg_Order_Value, Discount_Usage_Freq

## Output
- `upgrade_proba` score per customer
- `Propensity_Bucket` label

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib/Seaborn, Jupyter Notebook

## Files
| File | Description |
|------|-------------|
| `food_app_customer_data.csv` | Raw customer dataset |
| `scored_customers.csv` | Output with propensity scores |
| `predictive_analytics_customer_tiers.ipynb` | Full notebook |

## Team
| Name |
|------|
| Rushi |
| Akash Bhuyan |
| Rahul Atkare |
