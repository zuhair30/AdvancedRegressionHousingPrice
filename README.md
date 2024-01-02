# Project Name
HousePricing Case Study using Ridge and Lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and
- decide whether to invest in them or not.
The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Data file used is train.csv


## Conclusions
Data visualization , data cleansing , model building and evaluation steps are followed and delivered in Notebook
- Ridge and Lasso ALPHA vlaues are 2 and 0.00011
- Features that impact the model are the ones menitoned below
- One with + ve increase the Sale price while one with -ve coefficients tends to decrease rest which are zero are omited list is mentioned below
################
Positive Coefficients
OverallQual
MSZoning
TotRmsAbvGrd
Neighborhood
GarageCars
SaleType
MSSubClass
Street
Foundation_Stone
Exterior1st_Stone
CentralAir
FullBath_3
RoofStyle_Shed
BsmtExposure_Gd
Fireplaces_3
Heating_GasW
################
Negative Coefficients
GarageFinish_None
BsmtFinType2_None
BldgType_Duplex
Electrical_Mix
Functional_Mod 
## Technologies Used
- python 3
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

##


## Contact
Created by [@zuhair30] - feel free to contact me! on email as well zuhair30@gmail.com


