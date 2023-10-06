# Project_Phase_2

## Overview

### Business understanding

Stakeholder : Customers and Investors searching for affordable houses to buy or investing in .

Business Problem: Price prediction for the houses based on the data provided.

### The data 
Column Names and Descriptions for King County Data Set
id - Unique identifier for a house
date - Date house was sold
price - Sale price (prediction target)
bedrooms - Number of bedrooms
bathrooms - Number of bathrooms
sqft_living - Square footage of living space in the home
sqft_lot - Square footage of the lot
floors - Number of floors (levels) in house
waterfront - Whether the house is on a waterfront
Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
view - Quality of view from house
Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
condition - How good the overall condition of the house is. Related to maintenance of house.
See the King County Assessor Website for further explanation of each condition code
grade - Overall grade of the house. Related to the construction and design of the house.
See the King County Assessor Website for further explanation of each building grade code
sqft_above - Square footage of house apart from basement
sqft_basement - Square footage of the basement
yr_built - Year when house was built
yr_renovated - Year when house was renovated
zipcode - ZIP Code used by the United States Postal Service
lat - Latitude coordinate
long - Longitude coordinate
sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors

### Data Understanding
The Data Contains Multiple Features of Houses that are in King County.
Some of them include:
Dates houses were sold and renovated. The prices,bedrooms,bathrooms, their
co-ordinates(latitudes and longitudes) and more.
We will be performing data analysis and regression on these

### Modeling for Continuous Data
After preprocessing and analysis of the data.
Here is the final model summary results for the continuous data

### Regression Diagnostics
R-squared: Suggests that about 47% of the variance in dependent variable (price)
is explained by the plot.
The f-statistic and the pvalue of the model suggests that it is statistically
significant.
The pvalues of the coefficients indicate independent variables are statistically
significant in predicting the dependent variable(reference the jupyter notebook)

### Modelling for
R-squared: The model explains about 63% of variance in dependent variable(price).

The f-statistic and the pvalue suggests the overall model is statistically significant.

The low pvalues of the coefficients determine that the inpendent variables are
statistically significant in predicting the price.

### Model for the Categorical Data
R-squared: About 59% of the variance in the dependent variable is explained by the
model.
The high f-statistic and the low pvalue compared to the previous one before dropping says the
model has improved and the model is statistically significant as well as the pvalue.

## Recommendations
Based on the models
I recommend to potential buyers and investors to invest or buy houses that have additional lot footage and basement footage.
Considering the houses are in king county, for each increase in latitude and longitude the house prices are set to increase by about
$648K and $300K respectively.
Houses having 1.5 bathrooms is associated with a decrease in house price by $147,300 in this model.While a house with 8 bathrooms is
associated with an increase in $4,358,000. So buy houses with more bathrooms.
Consequently, a house with 1.5 floors has an increase of $53,800 and it decreases while floors are added with 3 floors having
a decrease of $107,700.
Houses that have waterfront are increase by approximately $458K than those that dont have waterfront.
If a house has an excellent view , its value is set to increase by about $267K with its value decresing as the view quality decreases.
