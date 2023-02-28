# Final-Project-Statistical-Modelling-with-Python For Toronto, ON, CA

## Project/Goals
In this project, we use three different APIs, CityBikes for collecting city bikes data, and FourSquare and Yelp for collecting venues information. The effect of independent variables will be investigated on the target and a multivariable regression model will be created. 
This prossess is performed for the city of Toronto, ON, CA. As an extra work, also prossess is performed for the city of Rio de Janeiro and presented [here](https://github.com/SalvaSamimi/Project-2-Statistical-Modelling-with-Python-Rio-de-Janeiro.git/) 



## Processes:
### 1- Getting CityBikes network and stations data using CityBikes API. Considered parameters are described in 'city_bikes.ipynb'. Target parameter is free_bikes.

### 2-Examining the parameters that can be provided by FourSquare and Yelp APIs, and understanding the groups that can be provided by each API

### 3- Selecting independent variable. Considered parameters are described in 'yelp_foursquare_EDA.ipynb'

### 4- Getting venues data using FourSquare and Yelp APIs

### 5- Comparing FourSquare and Yelp data to select proper data for venues

### 6- EDA, cleaning, visualization

### 7- Data integrating using CityBikes and FourSquare/Yelp venues data

### 8- Converting CityBikes, FourSquare, and Yelp data to SQLite3 database

### 9- Building regression model and model optimization


## Results
Backward and forward multivariate linear regression method has been used for modeling. According to the existing recommendations, the backward method is more suitable and widely used, and we refer to its results.

It is obvious that one of the effective parameters on the target is empty_slots parameter, which is confirmed by the analysis. Another parameter that is determined from the modeling is educational centers (education parameter). It can be said that most users of the bike network are students.

Since I have performed a similar analysis for 'Rio de Janeiro' and different results were observed, it is concluded that culture and climate play a significant role in the results of the analysis.


## Challenges 
1- Selecting Independent variables: In order to select independent variables, a preliminary study should be done on the relationship between the selected parameters and the target

2- Getting data from FourSquare and Yelp APIs due to request limitations and network loads


## Future Goals
Since some other factors such as population, age of people in any area, gender, season, and different days of week and time of data retrieving from CityBikes affect the target, it's nice to consider these factors in modeling.


