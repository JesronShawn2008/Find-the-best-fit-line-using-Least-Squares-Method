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
import matplotlib.pyplot as plt
x = np.array([1, 2, 3, 4, 5])   
y = np.array([2, 4, 5, 4, 5]) 
n = len(x)
m = (n * np.sum(x * y) - np.sum(x) * np.sum(y)) / (n * np.sum(x ** 2) - (np.sum(x)) ** 2)
c = (np.sum(y) - m * np.sum(x)) / n
print(f"Slope (m): {m}")
print(f"Intercept (c): {c}")
y_pred = m * x + c
plt.scatter(x, y, color='blue', label='Actual data')
plt.plot(x, y_pred, color='red', label='Fitted line')
plt.xlabel('X')
plt.ylabel('Y')
plt.title('Univariate Linear Regression using Least Squares')
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
