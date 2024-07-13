# ML-2a
## Project Name: 
This is a Machine Learning Project 2a - House Pricing Prediction.
## Project Description: 
Building a Machine Learning Model to predict the House Pricing based on other influencing factors like Area, Main-road, Bedroom, Basement etc.
Dataset: It has 13 attributes including Price.
Link for Dataset: Attached

## Objective: 
To create an ML Model which can predict Housing Price.

## Tools & Methodologies:
Libraries Used: sklearn, model_selection, train_test_split
Statistics Used: Multiple Linear Regression, Various Inflation Factors, p-value, Recursive Feature Elimination
Checked Performance Using: mean_squared_error and r_squared

## Result:
Below is VIF table:

![image](https://github.com/user-attachments/assets/f24b6f63-b58b-440b-81e3-594ccfb75a19)

Below is Statistics table:

![image](https://github.com/user-attachments/assets/ad333bae-0578-4b60-ba40-f51366273512)

Based on above tables (VIF and P-Values) choosen the best attributes 1 by one selection process based on VIF<5 and P-Value<0.05

Later this one by one selection process automated using RFE (Recursive Feature Elimination) method. Below is table relsult of that.

![image](https://github.com/user-attachments/assets/671829d6-e368-425e-982b-bda453753010)

The above table shown the best infuencing attributes have been used to create the model to predic the housing price.

## Conclusion:
mean_squared_error:  0.011708002 # Meaning our model is not able to predict correctly 0.01% saying in other way model was 99% accurate.

r_squared:   0.6021721774706439  # Meaning in real life data if R^2 value is 60 and above, it is a good model. So, this is a good model
