# Prediction-of-Product-Sales

## The goal of this analysis project is a sales prediction for food items sold at various stores. The aim of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales 

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/ds.PNG">
</p>

**Author**: Jaime Ross

### Business problem:

The retailer/stakeholder would like a better understanding as to which properties of products and outlets play a crucial role in increasing product sales.


### Data:
The data used in this analysis was taken from the 2023 sales predictions.

This dataset had 8523 rows and 12 columns.


## Methods
- Data cleaning (removing duplicates, handling missing values, fixing inconsistencies in data, etc.)
- Data exploration (EDA, data visualisation,etc.)
- Data explanation (EDA, data visualization, etc.)
- Preparation for machine learning (data cleaning, imputation of missing values, scaling and encoding data, etc.)
- Modelling (Fitting prepared data on various models.)

## Results


#### Outlet Type VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/outtype.PNG">
</p>

> The above visual depicts the outlet location compared to the outlet sales.
> The best performing outlet type belongs to the Tier 2 location.

#### Outlet type VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/outlet sales.PNG">
</p>

> The above visual depicts the outlet type/store type compared to the outlet sales.
> Type 3 supermarkets have the highest outlet sales.

#### Mass Retail Price VS Outlet Sales

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Prediction-of-Product-Sales/blob/main/mrp.PNG">
</p>

> The above visual depicts the groupings for the mass retail price compared to the outlet sales.

## Model

Machine learning was completed by making use of the following regression models.

> Linear regression Model

> Random Forest Model

> Tune Random Forest Model


Metrics received from the above models

>## Linear Regression Model:
 -------------------------
> Test Metrics:
- MAE = 805.656
- MSE = 1,197,421.441
- RMSE = 1,094.268
- R^2 = 0.566

>## Random Forest Model:
--------------------------
>Test Metrics:
- MAE = 773.357
- MSE = 1,246,634.453
- RMSE = 1,116.528
- R^2 = 0.548

>## Tuned Random Forest Model:
---------------------------
>Test Metrics:
- MAE = 728.550
- MSE = 1,096,437.307
- RMSE = 1,047.109
- R^2 = 0.603

  
The best model out of all was the tuned random forest model with a max_depth of 5, N_estimators set to 110, and oob_score set to True. The tuned model managed to explain 60,3% of the variance in Y by making use of the features selected. The MAE for the tuned model was off by 728.55. The MSE for the model was 1,096,437.307. The RMSE was 1047.109.

The model has improved after tuning, however, making use of this model may not yield the most reliable results.

## Recommendations:

By looking at the above information we are able to derive the following:

- The store location type that has the highest outlet sales belongs to the Tier 2 location.
- The outlet types that have the highest outlet sales belong to the type 3 supermarkets.
- An increase in mass retail prices has a positive effect on the total outlet sales.


## Limitations & Next Steps

By looking at the above information, the stakeholders are able to make use of the insights provided to make necessary decisions that would benefit the company, such as the optimal store size and type as well as the best-selling products.


### For further information


For any additional questions, please contact jaimeross.tech@gmail.com
