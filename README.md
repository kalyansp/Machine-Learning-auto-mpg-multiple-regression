# Machine-Learning-auto-mpg-multiple-regression
Predicting car fuel efficiency (MPG) from car specs using Multiple Linear Regression | Auto MPG dataset


Miles per gallon (MPG) for cars from the 1970s and 80s using Multiple Linear Regression.

## Dataset
- **Source:** UCI Machine Learning Repository — Auto MPG
- **Records:** 398 cars
- **Features:** Cylinders, Displacement, Horsepower, Weight, Acceleration, Model Year, Origin

## What I did
- Detected and handled hidden missing values (`?`) in Horsepower
- Checked correlations to identify which features impact MPG the most
- Trained a Multiple Linear Regression model on 80% of the data
- Evaluated predictions on the remaining 20%

## Key Findings
- Heavier cars and bigger engines → lower fuel efficiency
- Newer cars and Japanese/European origin → higher fuel efficiency
- RMSE of ~2.86 MPG on a range of 9–46 MPG

## Libraries
Python · NumPy · Pandas · scikit-learn · Matplotlib
