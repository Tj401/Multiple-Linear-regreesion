What Is My Purpose?

A. To predict the mileage of an auto basing on the input variables.

How Did I Do This?

A. I have gathered the auto data of the various cars online. After converting the the data to pandas dataframe. I have made the MPG as target variable or Y and input variables as HP,VOL,SP,WT. I have checked the basic EDA process and whether the data is following Normal distribution or not, which is the basic thing to check, to make sure there is no multi collinearity problem. Aftre making sure, I splitted the data into train and test. I have tried to input the data into the linear model and find out the coefficients and accurancy prediction. I have found out that p values of Wt and Vol have been > 0.5 which repsrensts they have high correlation value. so i need to find out the influential factors in the Wt and Vol and remove them, by plotting a influential plot. Thus by identiying the influentual data, i have removed them from the main data file and tried to create a linear model and predicted the outcome. 


