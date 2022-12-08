Predicting the price of a car using linear Regression Algorithm
Data Collection: Data was collected from 1985 price list of different car in the form of csv.

Data Cleaning:- Missing row was either replaced by mean for numerical type data or by maximum frequency for categorical type data and also dropped if the price data was missing as per the business needs.

Formatting: Checked the format of each column and changed the data type using astype function in Pandas.

Standardize: converted the mpg to Km/L by dividing 235 by the actual data.

Normalize: used MinMax Scaler to scaled the data between 0 to 1.

EDA Exploratory  Data Analysis:-  Data was analysed to see what are the factors which is dependent on the price of the car like Horse-power,engine size,city-mpg,etc

Model Development: A  model was developed using Single Linear regression, Multiple linear regression and polynomial regression.

Model Evaluation: Based on the Root mean square error(RSME) and Mean squared error (MSE) we found that Multiple Linear regression was best fitted with the least Mean-Squared Error of 1.2X10^7 and R-Squared value of 0.8093 (80.93%)

