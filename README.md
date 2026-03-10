#### Flight Price Prediction using Machine Learning

#### Objective : 
Flight ticket prices change frequently due to demand, seasonality, and airline policies. Predicting ticket prices can help travelers plan bookings and help companies analyze pricing patterns. The goal of this project is to develop a machine learning model capable of predicting flight ticket prices based on historical flight data.

#### Project Overview : 
This project aims to predict flight ticket prices using machine learning algorithms. 
Airfare prices fluctuate based on multiple factors such as airline, departure time, route, and number of stops.

#### Dataset

The dataset used in this project contains flight booking details including:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Duration
- Total Stops
- Additional Information
- Ticket Price (Target Variable)

The dataset was preprocessed and cleaned before building machine learning models.

#### Technologies Used : 
Programming : Python
Libraries : NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
Tools : VS Code

#### Table of Contents : 

1. Data Collection
2. Import Necessary Libraries
3. Data Loading & Inspection
4. Data Cleaning & Preprocessing
5. Exploratory Data Analysis(EDA) & Data Visualization
6. Label Encoding
7. Feature Selection using VIF(Variation Inflation Factor)
8. Feature Scaling
9. Model Building - Linear Regression, Decision Tree Regressor, Random Forest Regressor
10. Model Evaluation - Using metrics like Mean Absolute Error(MAE), Mean Squared Error(MSE), R2 Score, Mean Absolute Percentage Error(MAPE) and Root Mean Squared Error(RMSE)
11. Visualization of Predicted Values and Actual Values
12. Insights & Final Summary of the Project

#### Insights from Exploratory Data Analysis(EDA) :

**1. Airline Price Comparison Insight :**

- From the airline-wise price distribution analysis, I observed that Vistara and Air India flights have significantly higher ticket prices compared to other airlines such as Indigo, SpiceJet, AirAsia, and GO First.

- The average ticket price for Vistara was around ~29,000 – ~30,000, while Air India ranged between ~23,000 – ~25,000.This indicates that these airlines may offer premium services or business-class options, which increases the overall ticket price.

**2. Departure Time vs Ticket Price Insight :**

- From the analysis of days left before departure vs ticket price, I observed a trend where ticket prices tend to decrease as the departure date approaches in this dataset.

- This suggests that airlines may reduce ticket prices closer to departure time in order to fill remaining seats and maximize occupancy.


**3. Economy vs Business Class Insight :**

- The analysis of ticket class vs price showed that Business class tickets are significantly more expensive than Economy class tickets.

- This price difference is especially noticeable in Vistara and Air India flights, where business-class fares are much higher due to premium seating, additional services, and enhanced travel comfort.


**4. Passenger Travel Pattern Insight :**

- The dataset analysis also revealed travel behavior patterns among passengers. Most flights were operated by Vistara and Air India, indicating high passenger demand for these airlines. Additionally, flights were observed to arrive mostly during morning, evening, or night time slots, suggesting that airlines schedule arrivals during peak travel hours.

- The most frequent destination cities were Mumbai and Delhi, indicating these cities act as major travel hubs.
Furthermore, the majority of passengers booked Economy class tickets rather than Business class, showing that most travelers prefer cost-effective travel options.

**Business Insights :**

*1. Premium airlines tend to charge higher fares due to better services and premium seating options.*
*2. Airlines may lower prices to avoid empty seats.*
*3. Seat class is a major driver of ticket price variation.*

#### Machine Learning Models :

The following models are implemented and evaluated :

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

#### Model Evaluation :

Model performance was evaluated using the following metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

#### Results :

**Random Forest Regressor** performed the best. It achieved the highest R2 score ~ 0.98% and the lowest prediction errors, indicating superior predictive performance. The model successfully captured complex relationships within the dataset and significantly reduced prediction errors compared to other models.

#### Visualizations :

- Distribution plots
- Feature importance charts
- Model comparison graphs

#### Future Improvements

- Hyperparameter tuning
- Testing additional models such as XGBoost
- Deploying the model using a web application

## Conclusion

This project demonstrates how machine learning techniques can be used to predict flight ticket prices. 
Through data preprocessing, exploratory analysis, and model evaluation, the Random Forest Regressor was identified as the most effective model for accurate predictions.

## Author

Aishwarya Savanth
Aspiring Data Scientist | Machine Learning Enthusiast
