# Linear-Regression-on-Kingston-County-House-Dataset
## Objective 
In this project, we looked at the the various features that influence the price of a home in King's County. We analyzed these features, developed and tested models that would predict the price of the home
## Tools (all using Python and its various libraries)
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit Learn
## Data:
The data used was in csv format from Kaggle.
It had 20,000 data points.

The features were as follows:
id, date, price, bedrooms, bathrooms, sqft_living, sqft_loft, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, latitude, and longitude.
![Distribution of select features](https://user-images.githubusercontent.com/104419109/177050924-0e77844e-bb52-45d9-964e-442985ab759c.png)


## Taking a closer look at the data
![image](https://user-images.githubusercontent.com/104419109/177050874-8d13572d-757b-4c9a-8869-99881ec73e20.png)

## Modeling
After cleaning the data, examining various correlations, feature engineering, and determining iif the dataset was a good candidate for a Linear Regression, we were able to run a Polynomial regression model and achieve an accuracy rate of 70.7%.

## Conclusion
Complex Model_2 gives us R-squared (testing) score of 0.707. From above reports, we can conclude that Polynomial regression for degree=3 is the best solution.
