# Intro_AI_Final_Project
### Subject: DSCI6612-Intro to AI_Final_Project
### Team members:
    1. Name: Veera Venkata Sunil Kumar Seelam	
    2. Name: Sowmya Davuluri
   

## INTRODUCTION

 - We have taken a dataset from Kaggle.com which has used car informations
 - We used this data to predict the price based on relevant features available in the dataset 
 - The database has been created with data on their sales upto previous year
 - We are using machine learning techniques for price prediction
 - This dataset is going to provide the estimation quote of price based on data features entered by the user
 - It will help to guide the users to estimate the price for the used cars

## SYSTEM REQUIREMENTS AND PRE-REQUISITES

 - OS: Mac, Linux or Windows
 - Software: Python 3.0 or later
 - OS :Mac,Linux or Windows
 - Python3.0 or above
 - Jupyter Lab
 - Django

## ABOUT THE DATASET

## Fields:

 - dateCrawled- series object
 - name-series object
 - seller-series object
 - offerType-series object
 - price-series int
 - abtest-series object
 - vehicleType - series object
 - yearOfRegistration- series int
 - gearbox- series object
 - powerPS- series int
 - model- series object
 - kilometer- series int
 - monthOfRegistration- series int
 - fuelType - series object
 - brand- series object
 - notRepairedDamage - series object
 - dateCreated - series object
 - nrOfPictures- series int
 - postalCode- series int
 - lastSeen - series object

## Models implemented:

 - Linear Regression
 - K-Nearest Neighbors
 - MLP Regressor
 - Decision tree
 - Random Forest

## Attributes used:

 - Price
 - vehicleType
 - gearbox 
 - powerPS 
 - model 
 - kilometer 
 - fuelType 
 - brand
 - postalCode
 - vehicleAge


## DATA CLEANSING

 - Reformatted existing columns for easier analysis.
 - NaN, space values filled with mean, median and mode.
 - Conversion of few columns to date-time and integer values as needed for analysis.


## STEPS TO EXECUTE THE CODE
 
 - pip install below packages:
 	- Pandas
 	- Numpy
	- Sklearn
 	- matplotlib
 	- seaborn
 - Simply place the data in a separate directory and name it as 'Data'
 - run the .ipynb file and execute the code

## UI
 
 - We have designed the UI based on the above model in a clickable format and used it to predict the price 
 
## Conclusion

 - We evaluated used-car price prediction using Kaggle dataset which gives an accuracy of 93% with RandomForest Model.
 - The most relevant features used for this prediction are price, year, Power_ps, and vehicleAge by filtering out outliers and irrelevant features of the dataset. 
 - This model gives us good accuracy when compared to the other models.

## FUTURE WORK

 - To collect data for more cars
 - More information of cars in the current dataset
 - To adjust model hyper-parameters, by using RandomizedSearchCV

