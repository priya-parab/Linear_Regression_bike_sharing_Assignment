# Multiple Linear Regression Model For The Prediction Of Demand For Shared Bikes
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information

* Problem Statement

  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

* The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands.

* Business Goal:
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions

As per our final Model, the top 3 predictor variables that influences the bike booking are:

Temperature (atemp) - A coefficient value of ‘0.383568’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.383568 units.

Year (yr) - A coefficient value of ‘0.240592’ indicated that a unit increase in year variable increases the bike hire numbers by 0.240592 units.

season_spring, windspeed,weathersit_light_snow, weathersit_Mist+Cloudy are negative coefficients which decrease the bike hire numbers

month_Mar, month_Oct and month_Sep - A coefficients value of 0.062384, 0.092330 & 0.084001 indicated that a (Mar, Oct & Sep)month, increases the bike hire numbers.

Working_day, weekday_Sat - A coefficient value indicated that a working_day & weekday_Sat, increases the bike hire numbers.

**Business Goals

Temperature could be a prime factor for making decision for the Organisation. <br>
We can see demand for bikes was more in 2019 than 2018. <br>
Working days, weekday_Sat and Month of march,Oct and sept as they have good influence on bike rentals. So it would be great to provide offers on this days.

## Technologies Used

- Python - version 3.0
- Numpy
- Pandas
- Seaborn
- Matplotlib
