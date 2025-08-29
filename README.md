# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Mean Calculation
2. Least Squares Method (Slope Calculation)
3. Intercept Calculation
4. Prediction

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
import numpy as np
import matplotlib.pyplot as plt

# Input data: hours studied and corresponding marks
hours = np.array([1, 2, 3, 4, 5])
marks = np.array([35, 40, 50, 60, 65])

# Calculate the means
x_mean = np.mean(hours)
y_mean = np.mean(marks)

# Calculate slope (m) and intercept (c) using least squares
numerator = np.sum((hours - x_mean) * (marks - y_mean))
denominator = np.sum((hours - x_mean) ** 2)

m = numerator / denominator
c = y_mean - m * x_mean

print(f"Training complete. Slope (m): {m:.2f}, Intercept (c): {c:.2f}")

# Predict marks for a given number of hours studied
def predict_marks(hours_studied):
    return m * hours_studied + c

# Example: Predict marks for a student who studied 3.5 hours
hours_input = 3.5
predicted_marks = predict_marks(hours_input)
print(f"Predicted marks for {hours_input} hours of study: {predicted_marks:.2f}")

# Plot the data and the regression line
plt.scatter(hours, marks, color='blue', label='Original Data')
plt.plot(hours, predict_marks(hours), color='red', label='Regression Line')
plt.scatter(hours_input, predicted_marks, color='green', label='Prediction Point')
plt.xlabel('Hours Studied')
plt.ylabel('Marks Scored')
plt.title('Simple Linear Regression: Hours vs Marks')
plt.legend()
plt.grid(True)
plt.show()
```
Developed by: Shivasri
RegisterNumber:  212224220098
*/


## Output:
<img width="1919" height="1110" alt="image" src="https://github.com/user-attachments/assets/bcced26d-e028-485d-aa8f-cd3cf5cede7a" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
