# SQL Analysis
**SQL Analysis: Zomato Dataset Exploration**

In this project, I delved into the Zomato dataset using SQL to gain insights into the operations of the popular restaurant aggregator and food delivery service, Zomato. The dataset contains over 9000 rows with columns such as Restaurant_id, Restaurant_name, City, Location, and Cuisines, among others.

**Data Exploration:**
During the exploration phase, I focused on several key aspects:
1. Reviewed table details including column names, data types, and constraints.
2. Identified and removed duplicate values in the RestaurantId column.
3. Streamlined the dataset by removing unnecessary columns.
4. Merged two different tables and added a new column, Country_Name, using the primary key as the CountryCode column.
5. Corrected misspelled city names to ensure data accuracy.
6. Utilized window functions to calculate rolling counts of restaurants, providing a dynamic view of restaurant numbers over time.
7. Calculated the minimum, maximum, and average values for votes, rating, and currency columns.
8. Created a new category column for restaurant ratings to facilitate analysis.

**Data Analysis:**
Through thorough analysis, I unearthed several intriguing insights:
1. The majority of data (90.67%) is related to restaurants listed in India, with the USA accounting for 4.45%.
2. Only 28.01% of restaurants in India and 46.67% in the UAE offer online delivery options, out of 15 countries in the dataset.
3. Focusing on Indian restaurants, I discovered that Connaught Place in New Delhi boasts the highest number of listed restaurants (122), followed by Rajouri Garden (99) and Shahdara (87).
4. North Indian cuisine is the most popular in Connaught Place.
5. Of the 122 restaurants in Connaught Place, only 54 offer table booking facilities.
6. Restaurants with table booking facilities in Connaught Place, New Delhi, have an average rating of 3.9/5, compared to 3.7/5 for those without.
7. The best moderately priced restaurant (<1000 for two) with a rating > 4, votes > 4, and offering table booking and online delivery with Indian cuisine is located in Kolkata, India, named 'India Restaurant' (RestaurantID - 20747).

This project provided valuable insights into the restaurant industry, particularly in India, and showcased the power of SQL for data exploration and analysis in real-world business scenarios.
