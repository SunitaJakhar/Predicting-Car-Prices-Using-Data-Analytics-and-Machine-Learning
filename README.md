# Car Price Prediction Using Data Analytics and Machine Learning

# Project Aim and Methodology:

The purpose of this report is to use predictive and machine learning models to analyse the given Car dataset and predict car prices based on their features. The car dataset contains features about different car attributes, such as: Engine size, Horsepower, Fuel type, Body style, Normalized_losses, Engine type, City-mpg, Price (Target Variable), etc., which makes it a perfect example to apply various regression techniques such as Linear Regression, Random Forest and Logistic Regression and build a predictive model for car prices.

The methodology includes identifying the key car features that directly affect price and the relationships among variables. Additionally, the step-by-step data analysis process includes data collection, data preprocessing (cleaning & handling missing values), data engineering, exploratory data analysis, Machine learning model development, model evaluation using accuracy and confusion matrix, data visualisation, and finally, the business insights and recommendations on how the automotive industry can benefit by using such machine learning techniques in a real-world business scenario for making informed decisions.  


# Summary of key Findings:

To summarise, a detailed exploratory data analysis was performed to identify the key features that directly impact the price of the car and to study the correlation of each of the features with the target variable “price”. Additionally, two machine learning models (Linear Regression & Random Forest Regressor) were built, trained and tested using the train_test_split technique, followed by performance evaluation to check the accuracy of the models’ performance. Overall, both the Machine Learning models demonstrated high accuracy in predicting the target variable “Price”. However, the Random Forest Regressor (80/20 split) outperformed the Linear regression model in predicting the car prices with a higher R² (Coefficient of Determination) and lower MAE (Mean Absolute Error) & MSE (Mean Squared Error) metrics, representing a high-performing model. 


# Business Insights & Recommendations:

Based on the analysis, the following are some key business insights and recommendations. The features that clearly correspond to higher prices are horsepower, engine size, and body dimensions such as body length and width, as all of these features showed a strong positive correlation with price. Hence, the automotive companies looking to produce higher-priced vehicles should focus on the aforementioned features as they are strong indicators of car performance and premium positioning. Businesses can also use the machine learning predictive model to support pricing strategies, market segmentation, and to make informed product design decisions.

Additionally, customers can use this model to understand how different features impact the car prices, and make informed purchasing decisions by gauging if the vehicle has been priced fairly compared to other vehicles having similar features.
