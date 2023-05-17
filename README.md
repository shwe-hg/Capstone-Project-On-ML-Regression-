# capstone-project-on-ML-Regression-

## Project Summary -

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Database

We have the data set which contains data like hour , temperature, humidity , rainfall,snowfall,windspeed,seasons,holiday ect

1.Date : year-month-day

2.Rented Bike count - Count of bikes rented at each hour

3.Hour - Hour of the day

4.Temperature-Temperature in Celsius

5.Humidity - %

6.Windspeed - m/s

7.Visibility - 10m

8.Dew point temperature - Celsius

9.Solar radiation - MJ/m2

10.Rainfall - mm

11.Snowfall - cm

12.Seasons - Winter, Spring, Summer, Autumn

13.Holiday - Holiday/No holiday

14.Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


## Data Cleaning And Feature Engineering

1. **Removing Duplicate Rows**

2. **Handling null values**

## Exploratory Data Analysis

ploting graphs for getting the clear information about dataset.


### *Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:*


1.Bar plot

2.Line plot

3.Heatmap

4.Scatter Plot

5.Pie Chart

6.Box Plot

7.violin plot 

8.Dist plot

9.Histogram plot

10.Reg plot

11.Point plot

##Models

1.Linear regression model

2.Lasso Regression

3.Ridge Regression

4.ElasticNet Regression

5.Polynomial Regression

6.KNN Regression model

7.Decision tree Regression model

8.Random Forest

9.Gradient Boosting

10.eXtreme Gradient Boosting Regression

11.LightGBM

12.CatBoost


##Conclusion


1.Preprocessing the data was one of the difficult challenges i faced.


2.There is a urge of high demand in the morning 8AM and in evening 6PM as the people might be going to their work at morning 8AM and returing from their work at the evening 6PM.


3.People prefered more rented bikes in the morning than the evening.


4.When the rainfall was less, people have booked more bikes except some few cases.


7.The Temperature, Hour & Humidity are the most important features that positively drive the total rented bikes count.


8.After performing the various models the lightGBM and Catboost found to be the best model that can be used for the Bike Sharing Demand Prediction since the performance metrics (mse,rmse) shows lower and (r2,adjusted_r2) shows a higher value for the lightGBM.



9.We can use either lightGBM or catboost model for the bike rental stations.


10.holiday or non-working days there is demands in rented bikes.


11.Using different plots made the EDA easy.


12.I have calculated MAE,MSE,RMSE,adjusted r2 and R2 score for each model. Based on r2 score will decide our model performance.


13.out of all seasons winter having less demand and summer is having more demand of bikes.


14.For the temperature below 0 deg celicus the bike rent count is significantly decreased because may be people don't want to ride bike in such cold temperature.



15. The bike rent count is high when solar radiation is low and it is decreasing while increase in Solar radiation .


