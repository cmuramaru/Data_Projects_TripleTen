# TripleTen Sprint 3 Project - Shopper Habits and Retention Rates
This project analyzes shopper habits and retention patterns using real user activity data. The goal was to understand where users drop off in the conversion funnel, how long they remain engaged after their first purchase, and what behaviors drive retention.

### ✨ Important Analysis Terms
`Conversion Funnel Analysis`: Tracks users from product views → add to cart → checkout → purchase.
"To calculate conversion rates, we used unique user counts at each step of the funnel:
- Product views (view)
- Cart additions (shopping_cart)
- Purchases (purchase)

Each step in the funnel was analyzed using the COUNTUNIQUE of users who performed that action. We then calculated:
- Total conversion: the percent of viewing users who eventually completed that step
- Conversion to next step: the percent of users who continued from one step to the next
The funnel approach helps identify where most users drop off and where optimizations (like better cart algorithms or remarketing) may be needed."

`Retention Analysis`: Cohort-based tracking to measure how user activity changes month over month.
"Recognizing accurate retention rates were found using a cohort analysis:

- Users were grouped into monthly cohorts based on their first purchase date
- Each cohort's activity was then tracked over the next four months
- The cohort age (0 to 4 months) measures how long after the initial purchase users remained active
- Retention was calculated as a percentage of users from the original cohort who were still active in a given month. We based the cohort age of the original cohort as month 1. This structure helps identify how quickly user engagement declines over time."

`Purchase Activity Insights`: Identifies patterns in first purchases, repeat customers, and churn.
`Data Visualization`: Interactive dashboards built with Tableau to present funnels, cohorts, and retention curves.
The dataset consists of user activity reports from September of 2020 to February of 2021, tracking events such as product views, additions to shopping carts, and purchases. This data was collected via event tracking on an e-commerce platform and includes both timestamps and user id. For this analysis, we focused on two areas:
- Conversion funnel: to understand how users move from viewing to purchasing
- Retention rates: to evaluate how long users remain engaged after their first purchase

### 🎯 Roots of Retention
Businesses often struggle to understand why customers leave after their first interaction. This project was built to help identify bottlenecks in the funnel, understand long-term engagement, and provide actionable recommendations to improve conversion and customer loyalty.

### Goal: reducing friction in the checkout stage and improving post-purchase engagement could significantly improve retention.

### 📸 Project Media

#### COVERSION FUNNEL
<img width="749" height="568" alt="CONVERSION FUNNEL" src="https://github.com/user-attachments/assets/da081768-0b71-4232-98b2-24736a10a49f" />

#### RETENTION RATES
<img width="861" height="568" alt="RETENTION RATES" src="https://github.com/user-attachments/assets/a05f4102-bd26-4148-baa4-768c940cbc26" />

#### COHORT ANALYSIS 
<img width="1140" height="568" alt="COHORT ANALYSIS" src="https://github.com/user-attachments/assets/a089dac6-ca7e-407a-8aba-f65565cf2fc8" />

### 📊 Results
Out of 10,453 users who visited the page and viewed a product only 29% put the item into the shopping cart, and a little over 10% sealed the deal. In terms of those who put an item into the shopping cart, 35% went on to complete the purchase. The biggest drop-off in the funnel occurs between the product view and the cart stage, indicating a potential area to optimize.

The retention analysis tracks user cohorts by the first month of their purchase. Each cohort begins with 100% retention at month 1 (by definition), and tracks the date of recurring purchases from their first purchase. In no month is there a retention rate above 10% in the following month except 2020-09 when retention rates hit 13%.  However, by month 4, most cohorts show near-zero retention, with only a few users remaining engaged. 2020-10 is the only cohort retaining just 1% of its users by month 4. This trend highlights a rapid drop-off in user engagement after the initial purchase, suggesting a need for stronger post-purchase retention strategies.

### 🔗 Project Access
[![Sprint 3 Project](https://img.shields.io/badge/-Sprint_3_Project-black?style=flat&logo=sprint_3_project&logoColor=white)](https://drive.google.com/drive/folders/1HDotsKke7-D66EMm3wWAg-9pf9JZiEKT?usp=drive_link)
