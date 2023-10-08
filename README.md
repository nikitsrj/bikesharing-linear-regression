# Bike-Sharing Case Study (Linear Regression)
Linear regression model to predict the performance of Bike Sharing company
## Table of Contents
* [Situation](#Situation)
* [Task](#Task)
* [Action](#Action)
* [Steps](#Steps)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Situation
- A bike-sharing system is described as a service where bikes are available for shared use, typically for a fee or sometimes for free.
- Many bike-sharing systems have docking stations where users can rent and return bikes.
- BoomBikes, a US bike-sharing provider, is facing a significant drop in revenue due to the ongoing COVID-19 pandemic.
- The company aims to develop a strategy to increase revenue once the pandemic ends and the economy recovers.
- BoomBikes wants to understand the post-pandemic demand for shared bikes in the American market.

## Task
- The company has hired a consulting firm to investigate the factors influencing the demand for shared bikes.
- Specifically, they want to identify the significant variables that predict bike demand and how well these variables explain demand fluctuations.
- The focus is on the American market.
- The goal is to model the demand for shared bikes using available independent variables.
- This model will help management tailor their business strategy to meet demand levels and customer expectations, especially in a new market.

## Action
- Data preparation involves converting certain numeric feature values, such as 'weathersit' and 'season,' into categorical string values to avoid misinterpretation of order.
- The column 'yr,' which indicates the years 2018 and 2019, was initially considered for removal due to having only two values. However, it is reconsidered as it reflects the increasing demand for bike-sharing systems each year.
- The dataset contains columns 'casual,' 'registered,' and 'cnt.' 'Casual' represents casual users, 'registered' represents registered users, and 'cnt' represents the total number of bike rentals (casual and registered combined).
- The model building process will use 'cnt' as the target variable to predict demand for shared bikes.

## Steps
- Reading and Understading the data
- Visualising the data and make initial inference
- Data Prepration for linear regression
- Splitting the data into training and test sets
- Build multiple models unti you find the fit model
- Residuals Analaysis of the train Data and Validation
- Making Predictions using the Final Model
- Comparison of Train and Test Dataset
- Recommendation
  
## Conclusion
Demand of bikes depend on year, temp, workingday, windspeed, sep, sat, Light_snowrain, Misty, summer and winter.
## Technologies Used
- Panda
- NumPy
- Seaborn
- Matplotlib
- sklearn
- statsmodel
-  
## Acknowledgements
- This project was inspired by UpGrad IIITB Program as a case study for AI/ML Course

## Contact
Created by [@nikitsrj] - feel free to contact me!
