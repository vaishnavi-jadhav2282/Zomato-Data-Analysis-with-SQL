**PROJECT OVERVIEW**

This project focuses on exploring and analyzing the Zomato dataset using SQL. The dataset contains over 9000 rows with various restaurant-related information such as Restaurant ID, Name, City, Location, Cuisines, Rating, Votes, Price range, and more. The goal is to use SQL
 for cleaning, merging tables, and applying window functions to derive insights on restaurant trends, customer preferences, customer ratings, popular cuisines, areas with most listed of restaurants, and service availability across countries, with a focus on Indian restaurants.
 
 **TOOLS & SKILLS USED**
 
- MySQL for scripts and queries

- SQL Window Functions

- Joins & CTEs

- Views & Aggregations
 
**DATA EXPLORATION STEPS**

- Inspected table schema and metadata

- Checked and removed duplicates based on RestaurantID

- Removed unnecessary columns

- Merged country data using Country Code

- Corrected misspelled city names

- Used window functions to compute rolling counts

- Explored min, max, and average values of votes, rating, and price columns

- Created rating categories

**KEY INSIGHTS**

- According to this Zomato Dataset, 90.59% of data is related to restaurants listed in India followed by USA (4.54%).

- Out of 15 Countries only 2 countries provide Online delivery options to their customers, to be precise only 28.01% of restaurants in India and 46.67% of restaurants in UAE provides online delivery options.

- As this dataset contains data most related to India, so I worked on gaining insights on Indian Restaurants.

- Connaught Place in New Delhi has the most listed restaurants (122) followed by Rajouri Garden (99) and Shahdara (87)

- The most popular cuisine in Connaught Place is North Indian Food.

- Out of 122 restaurants in Connaught Place only 54 restaurants provide a table booking facility to their customers.

- Average Ratings for restaurants with table booking facility is approx. 3.8/5 compared to restaurants without table booking facility is 3.6/5 in Connaught Place, New Delhi.

- The best moderately priced restaurant with an average cost of two less than 1000, a rating of more than 4, votes more than 1000 and provides both table booking and online delivery options to their customer with Indian cuisines is located in Kolkata, India named as 'India Restaurant’ (Restaurant ID - 20747)
