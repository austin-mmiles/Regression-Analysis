# Regression-Analysis
## Abstract:
### Real Estate Valuation:
Many factors are taken into consideration when estimating the price of a house. Using our statistical
knowledge, we create a model that uses necessary factors applying transformations to estimate the price of
real estate in the Sindian District. Our findings concluded that the distance to the nearest MRT station,
number of convenience stores in proximity, and latitude were the most important factors to the house price of
unit area.
### Concrete Compressive Strength:
There are seven concrete components as well as age, in our data set that influence the concrete compressive
strength. We created a model through statistical algorithms that help us dictate which of these components
are needed or not needed to estimate the concrete compressive strength.
## Problem and Motivation:
### Real Estate Valuation:
The data set was collected from the Sindian District, New Taipei City, Taiwan during the period of June 2012
to May 2013. Someone interested in purchasing or investing in a property in the Sindian District, New Taipei
City, or Taiwan, can learn which factors are important to look at how important they are. Although this data
set is only collected from a specific period, the conclusions we draw from our findings can probably be applied
to different time periods. However, the conclusions we draw in this project are to show the significance of
certain factors for this specific data set.
### Concrete Compressive Strength:
The data set was collected from the paper, Modeling of strength of high performance concrete using artificial
neural networks, by Dr. I-Cheng Yeh. This data can be useful to those who are interested in creating a level
of concrete compressive strength they desire. One would be able to learn which factors are more important
than others and be able to create their concrete at a price they want or create it at a quality they want.
## Data:
### Real Estate Valuation:
1. TDate (the transaction date)
2. Age (the house age)
3. Metro (the distance to the nearest MRT station)
4. Stores (the number of convenience stores in the living circle on foot)
5. Latitude (the geographic coordinate)
6. Longitude (the geographic coordinate)
We look at these variables to see how they affect the variable Price (the house price of unit area), which is
the most important variable customers will look at.
### Concrete Compressive Strength:
1. Cement (component 1)
2. Blast Furnace Slag (component 2)
3. Fly Ash (component 3)
4. Water (component 4)
5. Superplasticizer (component 5)
6. Coarse Aggregate (component 6)
7. Fine Aggregate (component 7)
8. Age
Concrete compressive strength is variable of interest and we will analyze the relationship it has with the eight
variables above.
## Questions of Interest:
### Real Estate Valuation:
Which variables are significant to the house price of unit area? How influential are these variables to the
house price of unit area? What variable transformations will improve the model?
### Concrete Compressive Strength:
Which variables are significant to the concrete compressive strength? What algorithm will give us the best
model? Are there any outliers that affect the model? Given that we know certain variables, can we estimate
or predict a concrete compressive strength?
## Regression Methods:
### Real Estate Valuation:
1. We had preliminary expectations between the predictors and the response, using logic and our basic
understanding of real estate.
2. Created a fitted linear model for the Price Per Unit Area of a house.
3. Tested for significance of predictors in a model using t-tests and hypothesis testing.
4. Tested to see if adding certain variables would be a significant addition to the model using ANOVA
tests and hypothesis testing.
5. Created a second fitted linear model for the Price Per Unit Area of a house and compared it to the
original using diagnostic plots and finding their AIC’s and RSS’s.
6. Transformed certain predictors logarithmically we found looking at a scatterplot matrix.
7. Tested to see if transforming the response has an effect using Box-Cox.
8. Tested a further transformation, a Box-Tidwell transformation, to attempt to create a better model.
### Concrete Compressive Strength:
1. Applied forward selection using BIC as a criterion function to get a model.
2. Performed diagnostic checks: residual vs. fitted, QQ plot, and Durbin-Watson test, to determine if
linear regression assumptions hold.
3. Checked for influential observations using Cook’s Distance.
4. Estimated a mean response for our predictor values.
5. Predicted a new response for our predictor values.
6. Applied backward selection using BIC as a criterion function to get a model.
