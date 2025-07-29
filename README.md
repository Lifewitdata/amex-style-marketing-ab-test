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

### 2. **Exploratory Data Analysis (EDA)**
- Distribution of post-offer spend and engagement scores
- Earn vs. burn behavior (points earned vs. redeemed)

### 3. **Statistical Analysis**
- Validated group balance before the offer
- Conducted A/B testing using **t-tests**
- Calculated **lift** in spend and redemption for treatment group

### 4. **Visualization**
- Histograms, density plots, and boxplots
- Redemption rate comparison
- Scatterplots of points earned vs. redeemed

### 5. **Advanced Analysis**
- Multiple linear regression to understand the effect of treatment after controlling for demographics and pre-offer spend

---

## Tools & Technologies

- **Language:** R
- **Libraries:** tidyverse, ggplot2
- **Version Control:** Git & GitHub

---

## Key Insights

- Treatment group (Group B) showed a **statistically significant increase in post-offer spending**.
- Redemption rates were higher for Group B.
- Engagement scores improved in the treatment group, suggesting positive impact of the offer.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/marketing-offer-effectiveness-analysis.git
