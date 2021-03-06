# Bike-Sharing-Assighnment

#### Problem Statement:
A bike sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

#### Company Requirements:
                - To Which Variables are significant in predicting the demand for shared bikes.
                - How well those varaibles describe the bike demands

#### I would be using Multiple Linear Regression model for analysis.

### Data Dictionary

	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
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
	
#### Packages Used
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. sklearn.model_selection - train_test_split
6. sklearn.preprocessing - MinMaxScaler
7. statsmodel.api
8. statsmodels.stats.outliers_influence - variance_inflation_factor

#### Steps Involved
1. Reading and Understanding the Data
2. Data Preparation
3. Exploratory Data Analysis
4. Splitting the Data for model building
5. Scalling
6. Model Building & Summary Stats of the Model
7. VIF
8. Refining the Model Based on rsquared and VIF
9. Residual Analysis
10. Predicting the Model
11. R-Score Analysis of Predicted Model
12. Model Equation

