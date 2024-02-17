# House Price Prediction with Linear Regression

## Overview
This project implements a linear regression model to predict house prices based on their square footage and the number of bedrooms and bathrooms. The goal is to create a predictive model that can assist in estimating house prices using key features.

## Table of Contents

- [Features](#features)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Usage](#usage)

### Features 

The features of a house prediction model using linear regression typically involve the input variables or factors that are considered in predicting the target variable, which, in this case, is the house price. Here are common features used in a house price prediction model using linear regression:

1. ***Square Footage (Size of the House)***:
   - The total square footage of the house is a crucial feature. Larger houses tend to have higher prices.

2. ***Number of Bedrooms***:
   - The number of bedrooms in a house is an important factor. Generally, houses with more bedrooms have higher prices.

3. ***Number of Bathrooms***:
   - The number of bathrooms is another significant factor. Houses with more bathrooms may be considered more luxurious and, therefore, might have higher prices.

4. ***Location (Geographical Features)***:
   - The location of the house can significantly impact its price. Factors like neighborhood, proximity to amenities, and the overall desirability of the area are considered.

5. ***Year of Construction or Renovation***:
   - The age or recent renovation of a house can influence its price. Newer or recently renovated houses may have higher values.

6. ***Amenities and Features***:
   - Special features such as a swimming pool, a fireplace, a garage, or high-end appliances can influence the house price.

7. ***Lot Size***:
   - The size of the lot or land associated with the house can contribute to its value.

8. ***Accessibility to Transportation***:
   - Proximity to public transportation or major roads can impact the price, especially in urban areas.

When implementing a linear regression model for house price prediction, it's essential to carefully select features based on their relevance and significance. Additionally, feature engineering techniques may be applied to enhance the model's predictive power. Regularization techniques can also be used to avoid overfitting when dealing with a large number of features.

### Dataset
The dataset used for training and testing the model is sourced from [Median House Prices for California Districts](https://www.kaggle.com/datasets/camnugent/california-housing-prices) derived from the 1990 census.
This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.
Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:

- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- median_house_value
- ocean_proximity

### Model Training
