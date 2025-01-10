# Business Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

# Business Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business. 

# Data Description
The  dataset, named "foodhub_orders.csv" contains the different data related to a food order. The detailed data dictionary is given below.

## Data Dictionary
  1. order_id: Unique ID of the order
  2. customer_id: ID of the customer who ordered the food
  3. restaurant_name: Name of the restaurant
  4. cuisine_type: Cuisine ordered by the customer
  5. cost_of_the_order: Cost of the order
  6. day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
  7. rating: Rating given by the customer out of 5
  8. food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
  9. delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

# Python Foundations

Perform an exploratory data analysis and provide actionable insights for a food aggregator company to get a fair idea about the demand of different restaurants and cuisines, which will help them enhance their customer experience and improve the business

# Skills & Tools Covered
  1. Numpy
  2. Pandas
  3. Seaborn
  4. Univariate AnalysisIvariate Analysis
  5. Exploratory Data Analysis
  6. Business recommendations
  7. Bivariate Analysis
