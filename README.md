# SQL — Food Delivery Operational Analysis

## Introduction
This project analyzes the performance of a food-delivery platform that connects customers, restaurants, and couriers.  
It focuses on delivery efficiency, customer satisfaction, and revenue growth using SQL analytics.
---
## Objectives
- Evaluate delivery time efficiency by city.  
- Rank top restaurants by customer ratings and order volume.  
- Assess courier performance based on delivery speed and ratings.  
- Examine monthly revenue trends and customer retention.
---
## Project Description
The dataset simulates operations of a food-delivery business across five major cities.  
It includes:
- **customers** (registration and city)  
- **restaurants** (cuisine type and location)  
- **couriers** (performance rating and city)  
- **orders** (linking all entities with delivery time, amount, and rating)
---
## Steps Taken
1. **Database Creation:** Built normalized tables for customers, restaurants, couriers, and orders.  
2. **Synthetic Data:** Inserted realistic records for > 2 000 orders.  
3. **Exploratory Analysis:** Verified data integrity and relationships.  
4. **Operational Queries:**  
   - Average delivery time by city.  
   - Top 5 restaurants by average customer rating.  
   - Courier ranking by speed and rating.  
   - Monthly revenue and order trend.  
   - Repeat customer rate (using CTEs).  
5. **Performance Indicators:** Calculated KPIs from SQL outputs.  
6. **Insights Summary:** Documented patterns and recommendations.
---
## Key Insights
- Miami had the fastest average delivery time (~ 28 min).  
- Couriers with ratings > 4.5 consistently delivered under 35 minutes.  
- Top restaurants maintained average ratings ≥ 4.7 with high order volumes.  
- Revenue trend shows steady growth 2020–2024.  
- ~ 35 % of customers placed repeat orders → moderate retention.
