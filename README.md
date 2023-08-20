# Prediction-of-Product-Sales
## The goal of this analysis project is a sales prediction for food items sold at various stores. The aim of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales 

**Author**: Jaime Ross

### Business problem:

The retailer/stakeholder would like a better understanding as to which properties of products and outlets play a crucial role in increasing product sales.


### Data:
Data can include source and high-level description (e.g. # obs)


## Methods
- Data cleaning (removing duplicates, handling missing values, fixing inconsistencies in data,etc.)
- Data exploration (EDA, data visualisation,etc.)
- Data explanation (EDA, data visualisation,etc.)
- Preparation for machine learning (data cleaning, imputation of missing values, scaling and encoding data,etc.)
- Modelling (Fitting prepared data on various models.)

## Results


#### Outlet Type VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/outtype.PNG">
</p>

> The above visual depicts the outlet location compared to the outlet sales.

#### Outlet type VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/outlet sales.PNG">
</p>

> The above visual depicts the outlet type / store type compared to the outlet sales.

#### Mass Retail Price VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/mrp.PNG">
</p>

> The above visual depicts the groupings for the mass retail price compared to the outlet sales.

## Model

Machine learning was completed by making use of the following regression models.

> Linear regression Model

> Random forest Model

Metrics received from the above models

>## Linear Regression Model:
 -------------------------
> Training metrics:
- MAE = 847.102
- MSE = 1,298,649.624
- RMSE = 1,139.583
- R^2 = 0.561

  
> Test Metrics:
- MAE = 805.656
- MSE = 1,197,421.441
- RMSE = 1,094.268
- R^2 = 0.566

>## Random Forest Model:
--------------------------
> Training metrics:
- MAE = 755.446
- MSE = 1,152,804.652
- RMSE = 1,073.687
- R^2 = 0.610

  
> Test Metrics:
- MAE = 728.550
- MSE = 1,096,437.307
- RMSE = 1,047.109
- R^2 = 0.603
Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact jaimeross.tech@gmail.com
