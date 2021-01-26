# House Price Prediction

![enter image description here](https://github.com/amar-chakka/HousingPrice_Prediction/blob/main/houseprice_image.png?raw=true)

Details about the project, what did you do, how did you do and any other relevant info that would be necessary for evaluators to judge your work.

This project was created as a part of the INSAID Term project to help customer in predicting house prices. The data was sources from the kaggle.

In this project the outcome is a prediction of price. 

Sale distribution is right skewed. Skewness is high so there would be more information in the tail as well.

There are 80 explanatory and 1 target variables with dtypes distribution : float64(3), int64(35), object(43)

Interestingly, Sales Price of few houses are high though they are built Old. They could be having unique features triggering this high value. Scatter plot brings a better view of high sales price basing on how old a property is. However, there are outliers.

In Feature Engineering, All Missing values are imputed, Columns are dropped which does not add much value & New Columns are created.

Dummies are created in Dataset for all categorical variables.

Outliers are removed based on appropriate value of quantiles [%]

Applied LinearRegression Model to predict the value

To check out my notebook, please click [here](https://github.com/amar-chakka/HousingPrice_Prediction/blob/main/houseprice-prediction_nbk.ipynb).
