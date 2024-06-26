# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Read the csv file.
### Step2
Get the value of X and y variables
### Step3
Create the linear regression model and fit.
### Step4
Predict the CO2 emission of a car where the weight is 3300kg, and the volume is 1300cm cube.
### Step5
Print the predicted output.

## Program:
```
Implementation of Multivariate Linear Regression
Developed by: MARIO VIOFER J
Register Number: 212223100032
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))
```
## Output:
### Insert your output

<br>![image](https://github.com/Mario-Viofer-J/Multivariate-Linear-Regression/assets/144979232/0bcc8510-7472-4924-afa1-11ef599ed073)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
