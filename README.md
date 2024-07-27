# car_price_prediction_project

# AIM:- 
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

# what does the project does?
1)This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2)It then predicts the possible price of the car.

# How this project does?
1) First of all the data was scraped from Quikr.com (https://quikr.com) Link for data: https://github.com/Swastik11-coder/car_price_prediction_project/blob/main/quikr_car.csv
2) The data was cleaned (it was super unclean :( ) and analysed.

3) Then a Linear Regression model was built on top of it which had 0.92 R2_score.

Link for notebook: https://github.com/Swastik11-coder/car_price_prediction_project/blob/main/car_price_prediction.ipynb

4) This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.
