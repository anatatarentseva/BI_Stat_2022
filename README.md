
The dataframe Boston built into the package MASK (506 rows and 14 columns) was used in this paper.

This dataframe contains the following columns:

- crim - per capita crime rate by town.
- zn - proportion of residential land zoned for lots over 25,000 sq.ft.
- indus - proportion of non-retail business acres per town.
- chas - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
- nox - nitrogen oxides concentration (parts per 10 million).
- rm - average number of rooms per dwelling.
- age - proportion of owner-occupied units built prior to 1940.
- dis - weighted mean of distances to five Boston employment centres.
- rad - index of accessibility to radial highways.
- tax -full-value property-tax rate per $10,000.
- ptratio - pupil-teacher ratio by town.
- black - 1000(Bk - 0.63)**2, where Bk is the proportion of blacks by town.
- lstat - lower status of the population (percent).
- medv -median value of owner-occupied homes in $1000s.

An analysis was carried out of how the average cost of houses (variable medv) depends on various factors.
The work was done in three steps.

Step 1. A complete linear model was built, having previously applied
the standardization of predictors. The model does not need to take into account the interaction
of predictors.

Step 2. Performed diagnostics of this model:

a. The linearity of the relationship was checked;
b. The influential observations was checked;
c. The independence of observations was observed;
d. The normality of the distribution and the constancy of the variance was observed;

Step 3. A graph of cost predictions was constructed from the variable that has
the largest coefficient module.
