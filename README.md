# Bike-Sharing System Demand Prediction
> Build a multiple linear regression model for the prediction of demand for shared bikes. Understand the demand for shared bikes among the people after the quarantine situation ends across the nation due to Covid-19.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In such an attempt, the company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- The Business Problem is to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    •	Which variables are significant in predicting the demand for shared bikes.
    •	How well those variables describe the bike demands

    - The goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 

- Data: The data used is a large dataset on daily bike demands across the American market based on some factors. It contain 730 records with a total of 30 features.
    Major features in the dataset are
    - instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not 
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The demand is high in pleasant and warm climate than in extreme climate.
- Year 2019 had higher demand than the previous year 2018.
- The demand is low in holidays than the usual days.
- The factors positively affecting the demand are:
    - temperature 
    - winter 
    - summer 
    - september
    - year
- The factors negatively affecting the demand are:
    - Humidity
    - November
    - January
    - Mist
    - July
    - December
    - Light Snow
    - Wind Speed

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Data Preprocessing, EDA - Pandas, Numpy, Python
- Data Visualisation - Maplotlib, Seaborn
- ML Model Building - Stats Model, Sklearn
- Model Evaluation - Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@skadangara] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->