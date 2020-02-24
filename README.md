
# Module 2 Final Project


## Project Summary

In this project, we are working with the King County House Sales dataset. 
We clean, explore, and model this dataset with a multivariate linear regression to predict the sale price of houses as accurately as possible.

![alt text](https://github.com/FarnazG/dsc-mod-2-project-v2-1-online-ds-ft-120919/blob/master/images/kc-map.gif "King County Map")


## Project breakdown

we have 3 main section to prepare our data and create the linear regression model:

#### 1. cleaning data including:

*importing libraries and available data files
*Ckecking for missing data and placeholders
*checking for data types
*checking for duplicateds and outliers
*save the final clean dataset to work with

![Datacleaning_jupyternotebook](https://github.com/FarnazG/dsc-mod-2-project-v2-1-online-ds-ft-120919/blob/master/DataCleaning-student.ipynb)


#### 2. preprocessing data including:

*Importing libraries and available data set.
*Data preprocessing for the linear regression modeling.
>>a) checking for multicollinearity of features
>>b) checking the distribution of predictors
>>c) encoding categorical variables

*Feature selection.
*Creating the model.
>>a) regression model sklearn
>>B) regression model ols

*Validating and interpreting the results.
>>a) finding the most effective features for predicting housing price
>>b) writing price estimating equation

![Modeling_jupyternotebook](https://github.com/FarnazG/dsc-mod-2-project-v2-1-online-ds-ft-120919/blob/master/Modeling-student.ipynb)


#### 3. Exploratory data analysis including:

Question1. How does the location affect the housing prices?
Question2. How does renovation affect the housing price?
Question3. How much difference is between the price of hoses with the waterfront view and others?
Question4. what are the most affective factors on the housing price?

![EDA_jupyternotebook](https://github.com/FarnazG/dsc-mod-2-project-v2-1-online-ds-ft-120919/blob/master/EDA-Questions.student.ipynb)



## Non-technical presentation

![presentation](https://github.com/FarnazG/dsc-mod-2-project-v2-1-online-ds-ft-120919/blob/master/presentation/presentation.pdf)



## Recommendations

In this project we created a model to explore the most important factors in housing market and predict the prices, based on our model:
**Estimated_price= -0.067 + 0.5 Grade + 0.39 Sqft_living + 0.25 lat + 0.2 waterfront - 0.1 yr_renovated.**

>> GRADE:overall grade given to the housing unit, based on King County grading system has the most effect on the price
>> SQFT_LIVING: square footage of the home is the second most effective factor
>> LOCATION: the latitude coordinate of the house is the third most effective factor
>> WATERFRONT: having a waterfront view is the forth important factor.
>> RENOVATION: Year when house was renovated is our last factor in the model.


## Conclusion 

The dataset deals with the real world data, there are always changes, updates, additions and errors in datas and their collections, so there will always be some degree of error in any model, for instance, data and likely to have a multiplicity of additional factors that are effecting housing prices which are missing from the data collected.
It is the matter of getting to the best possible approximate with the available data.


## Further work 

If there were more data (neighborhood crime rates, proximity/quality of schools, accessibility/quality of public transportation,etc), we could likely improve our model considerably.
Also, Perhaps a more complicated non-linear regression (polynomials) might make a better model, so we will continue to update and gather more data and explore different versions of models to keep improve our results.