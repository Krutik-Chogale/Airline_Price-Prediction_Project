# Airline_Price-Prediction_Project
## Goal of this Project:
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
#### This Project contains the dataset for flight data. The goal is to predict to the correct flight price based on the variables that you think are the right ones to make the prediction. The model's performance will be evaluated based on its ability to minimize the Root Mean Square Error (RMSE) between the model's predicted values and the actual flight prices.

#### The dataset is in CSV format, which consists of various features related to flight prices, such as departure city, destination city, date and time of flight, flight duration, airline, etc. Your mission is to extract valuable insights from this data and create a model that can predict flight prices as accurately as possible.

## Overview
The data has been split into two groups:
  1. train set ([train.csv](https://github.com/Krutik27401/Airline_Price-Prediction_Project/blob/main/data/test.csv))
  2. test set ([test.csv](https://github.com/Krutik27401/Airline_Price-Prediction_Project/blob/main/data/train.csv))
  
 The **Train set** should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “Flight_Price ”) for each flight.

 The **Test set** should be used to see how well your model performs on unseen data. For the test set, we do not provide the fare for each flight. It is your job to predict these outcomes. For each flight in the test set, use the model you trained to predict the price of the flight ticket.

## Data Dictionary

Here are the column values and their descriptions:

The columns are as follows: 

1. Flight_ID: A unique identifier for each flight.
2. Airline: The airline operating the flight.
3. Departure_City: The city from which the flight departs.
4. Arrival_City: The city where the flight arrives.
5. Distance: The distance between the departure and arrival cities (in kilometers).
6. Departure_Time: The time of day when the flight departs (in 24-hour format).
7. Arrival_Time: The time of day when the flight arrives (in 24-hour format).
8. Duration: The duration of the flight (in hours).
9. Aircraft_Type: The type of aircraft used for the flight.
10. Number_of_Stops: The number of stops during the journey.
11. Day_of_Week: The day of the week when the flight takes place.
12. Month_of_Travel: The month when the flight takes place.
13. Holiday_Season: Indication of whether the flight occurs during a holiday or a specific season.
14. Demand: A metric representing the demand for flights on that specific route.
15. Weather_Conditions: Weather conditions during the flight.
16. Passenger_Count: The number of passengers on the flight.
17. Promotion_Type: The type of promotion offered for the flight. 
18. Fuel_Price: The cost of fuel (per liter), which can significantly influence ticket prices.
19. Flight_Price: The price of the flight ticket.

> [!NOTE]
>For the Flight prices please refer [Submission.csv](https://github.com/Krutik27401/Airline_Price-Prediction_Project/blob/main/submission.csv).
