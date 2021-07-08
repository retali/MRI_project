# MRI_project
Macroeconomic Result Index (MRI), developed by Jose Ignacio Diaz Rettali.

Here is a presentation about the Macroeconomic Result Index:

https://retali.github.io/MRI_project/Fproject2.html

And some visualization at tableau-public: 

https://public.tableau.com/profile/jose.diaz5288#!/vizhome/jidrbook1/Sheet1?publish=yes

https://public.tableau.com/profile/jose.diaz5288#!/vizhome/JIDRBookUSAmri/Dashboard1

This project deals with two purposes:
1) Present an Index number to measure the result of the country's macroeconomic performance (MRI), and
2) Demonstrate that the real GDP per capita growth rate is a function of the MRI.

It will work with data from more than 40 countries in a period of 42 years.

The project has been worked in 6 groups of coding. 

The first group of coding (fproject1.ipynb) will work with advanced economies, the US and Canada.
The second is going to be with 15 countries from Latin America, and
the third, with 23 countries from Europe.
The fourth group deal with the relationship between the real GDP percapita growth rate and the
Macroeconomic Result Index, through the Rsquared (coefficient of determination).
The fifth and sixth groups deal with the data of each country by using machine learning concept
to handle the whole process of linear regression and validation of the model object.

This is to define the model object, fit the model to the data and make predictions with the model.
The model is: real GDP percapita growth rate (Y) = f(MRI) [ Y = aX + b + e (e = prediction error)]
They are also calculated the mean squared error (MSE), the correlation coefficient and the Rsquared.
It is used the predict function to calculate predicted values.
VALIDATION: In order to quantify our model against new input values, we often split the data into training and testing data. 
The model is then fit to the training data and scored by the test data. 
Sklearn pre-processing provides a library for automatically splitting up the data into training and testing.
It is used the Durbin-Watson test for serial correlation (autocorrelation) test.
It is shown the model fit by plotting the predicted values against the original data.

Advanced economies: 40 countries defined by the International Monetary Fund
All dataset were provided by the International Monetary Fund
https://www.imf.org/external/pubs/ft/weo/2019/01/weodata/weoselagr.aspx
It is also worked with the US and Canadian economies.
Macroeconomic Result Index (MRI) is an Index developed by Jose Ignacio Diaz Rettali

This analysis is based on the Macroecnomic Result Index (MRI)
MRI = (real GDP rate / (inflation rate + unemployment rate)) * 1000
This index is then related to the real GDP per capita growth rate.

The project includes working with excel, python-pandas-matplotlib, tableau and machine learning.


