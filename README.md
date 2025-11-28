# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
Program to implement univariate Linear Regression to fit a straight line using least squares.
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt
X = np.array([2,3,4,5,6])
y = np.array([4,6,8,10,12])
m = np.sum((X - X_mean)*(y - y_mean)) / np.sum((X - X_mean)**2)
c = y_mean - m * X_mean
y_pred = m * X + c                        
print(f"The slope is {m:.0f}")
print(f"The intercept is {c:.0f}")
print(f"The line equation : y = {m:.0f}x + {c:.0f}")
plt.scatter(X, y, label="Actual Data")
plt.plot(X, y_pred, label="Best Fit Line", linewidth=2)
plt.xlabel("X")
plt.ylabel("Y")
plt.title("Univariate Linear Regression (Least Squares)")
plt.legend()
plt.show()
Developed by: Jesron Shawn C J
RegisterNumber:  25012933
*/
```

## Output:
<img width="1159" height="657" alt="image" src="https://github.com/user-attachments/assets/28637a22-748a-4e23-b76b-45d5a423efd8" />



## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
