# Zomato Sales Analysis

![zomato_banner](https://github.com/user-attachments/assets/e785f64d-1721-4e01-bfae-7c884445e1fd)

## Business Problem Statement

The goal of this project is to explore the **Zomato** Restaurants dataset to gain meaningful insights into the dynamics of the food delivery industry. Specifically, we aim to identify the key factors that contribute to a restaurant's success, including elements like customer ratings, review counts, and cuisine styles. Through an analysis of customer sentiments reflected in reviews, we aim to understand the appeal of different types of restaurants, focusing on both order volume and the sentiment polarity of feedback. Ultimately, this project seeks to provide restaurant owners and managers with actionable recommendations for enhancing their establishment's performance and elevating customer satisfaction.

## Overview of Dataset:

1. **Food Item Categorization:** Analyze food and veg/non-veg status.
2. **Cuisine Variety:** Explore menu cuisine diversity.
3. **Sales Trends:** Investigate order patterns over time.
4. **Restaurant Distribution:** Assess restaurant presence globally.
5. **Demographic Analysis:** Explore user age, gender, marital status.
6. **Cuisine Popularity:** Identify trending cuisines across regions.
7. **Revenue Metrics:** Track sales performance indicators.
8. **Customer Satisfaction:** Analyze reviews and ratings.
9. **Geographic Insights:** Visualize sales distribution across regions.
10. **User Engagement:** Measure user interaction frequency.
11. **Competitive Benchmarking:** Compare against industry rivals.
12. **Growth Recommendations:** Offer actionable growth strategies.

## Key Measures

The following measures were created to drive insights in the dashboard:

- ActiveUsers
- CurrentYear
- CurrentYrSale
- Dynamic_Title
- GainCustomers
- LostCustomers
- Order_count
- PreviousYear
- PreviousYrSale
- Rating_Count
- Sales
- Subheading
- Top_N_Sales
- UserCount

## Data Transformation in Power Query

Data transformations were performed to clean and prepare the data before visualization. These included:

- Merging datasets for comprehensive insights.
- Creating calculated columns for better categorization.
- Filtering irrelevant data to enhance performance.

## Dashboard Overview

The dashboard contains the following visual pages:

> **Overview Page**

- Displays total quantity, sales, ratings, and order count.
- Breakdown of food items by category: Veg, Non-Veg, and Other.
- Visualizes top-performing cities by sales and a trendline of yearly sales growth.

> **User Performance Page**

- Overview of total users, active users, and orders placed.
- Insights into gained and lost customers with gender distribution.
- User distribution by age group.

> **City Analysis Page**

- Detailed city-wise analysis of sales, orders, gained and lost customers.
- Comparison of cities based on ratings and active users.

Check out the [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTEzMmVjYjctNmViYS00MWFlLTllNzQtMGFiN2ZlYjY0ZTcxIiwidCI6IjY0NWY1NDA5LWJkNjAtNDNhMS04ZmVmLTFhODNiNjU3YzIyMCJ9) 📊

## Key Insights

This data provides a great overview of Zomato's performance. Here are some key takeaways:

1. **Growth & Reach**:  
   - Operating in **150,281 locations** with **100,000 restaurant partners** is a strong indicator of its market penetration.  
   - The total **orders (150,281)** suggest a one-to-one order-location ratio, which could indicate relatively low frequency per location.

2. **Financial Metrics**:  
   - The **total sales amount is ₹987 million**, with **2 million units sold**, suggesting an average order value of around ₹493.  
   - The rating count (148,000) shows high user engagement, assuming these are customer reviews.

3. **Category Performance**:  
   - Non-Veg: ₹106 million in sales with a rating of 10,000
   - Veg: ₹122 million in sales with a rating of 12,000
   - Others: ₹24 million in sales with a rating of 927

4. **City-Level Trends**:  
   - Top-performing cities include **Tirupati, Electronic City, Baner (Pune), and Raipur**—suggesting demand isn't just limited to metros but also tier-2/3 cities.

5. **Sales Trend Over Time**:  
   - **2018 peak at ₹0.41B** shows strong growth.  
   - **2019 dip to ₹0.34B** suggests early signs of stagnation.  
   - **2020’s sharp fall to ₹0.14B** is likely due to COVID-19 restrictions.

## Recommendations

Here are some **recommendations** based on the analysis of Zomato's data:  

1. **Improve Order Frequency & Customer Retention**  
     - **Loyalty Programs**: Introduce reward points for repeat customers.  
     - **Subscription Plans**: Offer discounts for frequent users.  
     - **Personalized Recommendations**: Use AI to suggest food items based on past orders.  

2. **Boost Sales & Revenue**  
     - **Increase Average Order Value**: Offer bundle deals (e.g., combo meals, family packs).  
     - **Promotions on Low-Selling Items**: The "Others" category has low ratings and revenue; targeted discounts could drive sales.  
     - **Focus on High-Performing Cities**: Invest in marketing & partnerships in top cities like Tirupati, Electronic City, Baner, and Raipur.  

3. **Address Declining Sales Trend**  
     - **Expand Cloud Kitchens**: Offer exclusive Zomato-branded cloud kitchens in underperforming areas to boost sales.  
     - **Partner with More Restaurants**: Increase variety in cities where sales have dropped.  

4. **Improve Customer Feedback & Ratings**  
  - **Encourage More Reviews**: Incentivize customers to leave reviews for better engagement.  
  - **Resolve Negative Feedback**: Implement AI chatbots for quicker responses to bad ratings.  
