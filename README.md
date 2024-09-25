# Zomato_EDA_Project

## 1. Background and Overview

Zomato is one of the leading global food delivery and restaurant discovery platforms, offering services such as online ordering, restaurant reviews, and table reservations. In an effort to understand customer preferences and improve service offerings, this project undertakes an Exploratory Data Analysis (EDA) of Zomato's restaurant data. Through this analysis, the goal is to answer specific business questions that could help Zomato optimize their operations, identify trends, and enhance customer satisfaction.

This project utilizes Jupyter Notebook to explore and analyze the data, providing insights into restaurant types, customer engagement, ratings, spending behavior, and the performance of online vs. offline orders.

## 2. Data Structure Overview

| name                     | online_order | book_table | rate | votes | approx_cost(for two people) | listed_in(type) |
|--------------------------|--------------|------------|------|-------|-----------------------------|-----------------|
| Jalsa                    | Yes          | Yes        | 4.1  | 775   | 800                         | Buffet          |
| Spice Elephant            | Yes          | No         | 4.1  | 787   | 800                         | Buffet          |
| San Churro Cafe           | Yes          | No         | 3.8  | 918   | 800                         | Buffet          |
| Addhuri Udupi Bhojana     | No           | No         | 3.7  | 88    | 300                         | Buffet          |
| Grand Village             | No           | No         | 3.8  | 166   | 600                         | Buffet          |


## 3. Executive Summary

The analysis addressed six key business questions:

#### •	Customer Preferences:
o	What type of restaurant do the majority of customers order from?
o	Dining restaurants are preferred by a larger number of individuals.

•	Customer Engagement:
o	How many votes has each type of restaurant received from customers?
o	Dining restaurants have received the maximum votes from customers.

•	Restaurant Ratings:
o	What are the ratings that the majority of restaurants have received?
o	The majority of restaurants received ratings ranging from 3.5 to 4.

•	Spending Patterns:
o	What is the average spending per order for couples who primarily order food online?
o	The majority of couples prefer restaurants with an approximate cost of 300 rupees for two people.

•	Online vs Offline:
o	Which mode (online or offline) has received the highest ratings?
o	Offline orders received lower ratings in comparison to online orders.

•	Offline Order Trends:
o	Which type of restaurant receives more offline orders, enabling Zomato to provide targeted offers to those customers?
o	Dining restaurants primarily accept offline orders, whereas cafes primarily receive online orders. This suggests that customers prefer in-person dining at restaurants, but prefer online ordering at cafes.

## 4. Insights Deep Dive

•	Customer Preferences: The data reveals that dining restaurants are more popular for in-person orders, which may be attributed to the experience of dining out. Customers are more likely to order online from cafes, indicating a potential focus on convenience and faster service.

•	Customer Engagement: Restaurants with dining options receive a higher number of votes, likely due to more frequent interactions and customer feedback. This indicates that offering offline services can increase customer engagement and visibility.

•	Ratings and Satisfaction: The bulk of restaurants fall within the 3.5 to 4 rating range, which suggests that most customers are satisfied, but there may be room for improvement in service quality or food offerings to boost higher ratings.

•	Spending Patterns: Couples tend to prefer budget-friendly dining options, with the average cost being around 300 rupees for two. Zomato could leverage this data to offer deals and promotions aimed at this segment, particularly for online orders.

•	Online vs Offline Ratings: Interestingly, online orders receive better ratings than offline orders, indicating that the convenience and ease of online ordering may contribute to a better overall customer experience.

•	Offline Order Trends: Dining restaurants receive more offline orders compared to cafes, which see a higher volume of online orders. This insight can help Zomato create targeted offers to encourage more offline engagement at dining restaurants and boost online orders at cafes.

## 6. Recommendations

•	Optimize Promotions for Dining Restaurants: Since dining restaurants receive more offline orders, Zomato should focus on offering attractive deals and offers for in-person dining experiences. These could include table booking discounts or special in-house promotions.

•	Boost Online Engagement for Cafes: As cafes tend to attract more online orders, Zomato can promote these outlets through exclusive online deals, loyalty programs, or timed offers for delivery services, enhancing their appeal to online customers.

•	Improve Offline Customer Experience: Given that offline orders tend to receive lower ratings, Zomato should investigate potential areas for improving the in-person dining experience, such as faster service, better customer interaction, or enhanced ambiance.

•	Target Budget-Friendly Promotions: Since many customers and couples prefer restaurants with lower price points (around 300 rupees), Zomato can launch marketing campaigns that highlight affordable dining options, catering to budget-conscious consumers.



