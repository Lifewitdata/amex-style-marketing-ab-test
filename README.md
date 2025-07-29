# amex-style-marketing-ab-test

# Marketing Offer Effectiveness Analysis (A/B Testing)

This project evaluates the impact of a marketing offer on customer spending, redemption behavior, and engagement using **A/B testing techniques**.  
The dataset contains 100,000+ synthetic customer records generated in R, designed to simulate a loyalty/rewards program scenario similar to credit card reward systems.

---

## Project Objectives
1. Measure the effectiveness of a marketing offer in increasing:
   - Post-offer spending
   - Reward redemption rates
   - Engagement scores
2. Use statistical techniques to provide data-driven recommendations.
3. Build clear visualizations and insights that can be used by stakeholders for decision-making.

---

## Dataset Description

- **customer_id** – Unique ID per customer  
- **group** – Control group (A) or Treatment group (B)  
- **age, income, region** – Demographic information  
- **spend_before_offer** – Total spend in 3 months before the offer  
- **spend_after_offer** – Total spend in 3 months after the offer  
- **points_earned** – Loyalty points earned before the offer  
- **redeemed_points** – Loyalty points redeemed after the offer  
- **engagement_score** – Engagement level (0–100)

The dataset was generated synthetically to simulate realistic patterns.

---

## Steps Performed

### 1. **Data Preparation**
- Handled missing values and outliers
- Feature engineering: created redemption flag and spend change

### 2. **Exploratory Data A**
