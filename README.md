# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import pandas as pd and from sklearn import linear_model

### Step2
<br>Read the csv file from the drive

### Step3
<br>Drive the required list from the file

### Step4
<br>Print the list of the program

### Step5
<br>End the program

## Program:
```
#Implementation of Multivariate Linear Regression
#Developed By: Divya Sri V
#Register NUmber: 212224230070

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))


```
## Output:

### Insert your output

![image](https://github.com/user-attachments/assets/5b27caa3-2d64-4b95-8367-5220446f57dd)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
