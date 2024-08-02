# Predicting Restaurant Ratings on Zomato Using Machine Learning Models
## Problem Statement:
The goal of this project is to build a predictive model that can accurately forecast restaurant ratings on Zomato based on various features such as votes, cost, location, cuisines, and more. By leveraging machine learning techniques, particularly Decision Tree Regression and Random Forest Regression, we aim to understand the key factors influencing customer ratings and improve the decision-making process for restaurant management and marketing strategies.

## Project Description:
**Project Title:** Zomato Restaurant Rating Prediction Using Decision Tree and Random Forest Regression

**Objective:**
The primary objective of this project is to predict the ratings of restaurants listed on Zomato using machine learning models. By analyzing various features such as the number of votes, cost, location, cuisines, and more, we aim to build a robust model that can provide accurate predictions and valuable insights for restaurant owners and marketers.

**Dataset:**
The dataset used in this project contains information about restaurants in Bangalore, including their ratings, votes, cost for two, types of cuisines, location, and other relevant features. The data has been cleaned and preprocessed to ensure accurate and meaningful analysis.

**Data Cleaning:**
- Deleting redundant columns.
- Dropping duplicate entries.
- Handling missing values.
- Renaming columns for better readability.
- Cleaning individual columns to ensure consistency.
- Performing necessary transformations to make the data suitable for modeling.

**Data Visualization:**
Various plots and visualizations have been created to explore the relationships between different features:
- Distribution of Ratings, Cost, and Votes
- Analysis of restaurants delivering online vs. those that do not
- Restaurants allowing table booking or not
- Location-wise distribution of restaurants
- Top 20 locations with the highest number of restaurants
- Top 20 restaurant types
- Distribution of types of services offered
- Most popular cuisines in Bangalore
- Famous restaurant chains in Bangalore
- Top 20 popular casual dining restaurants
- Top 20 North Indian cuisine restaurants
- Relationship between cost and rating
- Distribution of votes and cost with online order availability
- Distribution of cost and votes with table booking availability
- Location-wise distribution of online orders
- Restaurants with table booking options relative to location
- Distribution of ratings with location, restaurant type, and types of services
- Best affordable restaurants in any location
- Analysis of cities with the highest purchasing power in Bangalore

**Modeling:**
Two machine learning models were employed to predict restaurant ratings:
- Decision Tree Regression:
     - R-squared (R²): 0.8529
     - Mean Squared Error (MSE): 0.0287
     - Root Mean Squared Error (RMSE): 0.1693
     - Mean Absolute Error (MAE): 0.0503

- Random Forest Regression:
     - R-squared (R²): 0.9083
     - Mean Squared Error (MSE): 0.0179
     - Root Mean Squared Error (RMSE): 0.1338
     - Mean Absolute Error (MAE): 0.0655

** The Random Forest model outperformed the Decision Tree model, indicating a better fit and higher accuracy in predicting restaurant ratings.**

** Feature Importance:**
The Random Forest model provided insights into the importance of various features:
- Votes: 35.63% importance, indicating a strong correlation between the number of votes and ratings.
- Cost: 11.10% importance, suggesting the price range significantly impacts ratings.
- Name: 10.74% importance, highlighting the influence of well-known or popular restaurant names.
- Cuisines: 10.66% importance, showing that the type of cuisines offered plays a crucial role in ratings.
- Reviews List, Location, Book Table, Rest Type, City, Online Order, and Type: These features also contribute to the model, albeit to a lesser extent.

## Conclusion:
This project demonstrates the effectiveness of machine learning models in predicting restaurant ratings on Zomato. The insights gained from feature importance analysis can help restaurant owners and marketers make informed decisions to enhance customer satisfaction and improve ratings. The Random Forest model, with its high R² value and lower MSE and RMSE, proves to be a robust choice for this prediction task.
