# Car Price Prediction
This repository contains a car price prediction model using linear regression and Lasso. The model is trained on the car data.csv file, which contains information on various used cars such as year, selling type, transmission type, fuel type, etc. The goal is to predict the selling price of a used car based on these features.

## Requirements
The following packages are required to run this code:

pandas

matplotlib

seaborn

scikit-learn

## Usage
1.Clone the repository to your local machine.

2.Load the data from the car data.csv file into a pandas dataframe.

3.Encode categorical variables such as "Fuel_Type", "Seller_Type", and "Transmission".

4.Split the data into training and testing sets.

5.Train a linear regression and Lasso model on the training data.

6.Evaluate the performance of the models using the R^2 error metric.

7.Plot the actual vs. predicted prices to visualize the accuracy of the models.

## Results
The linear regression model achieves an R^2 error of 0.87 on the training data and 0.83 on the test data. The Lasso model achieves an R^2 error of 0.84 on the training data and 0.87 on the test data.

## Note
This is just a sample code and not intended for commercial use. Further improvements can be made to the model and the data used to train it.
