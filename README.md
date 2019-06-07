# Predictive-Modeling
This repository contains 2 problems of predictive modelling

## 1.Bike rental system
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated 
via a network of kiosk locations throughout a city.In this we are asked to combine historical usage patterns with weather data in order 
to forecast hourly bike rental demand.

Our train dataset conatains following variables:
<img src="Screenshot (147).png" style="width:50%;float:left">

Our aim is to predict the 'count' variable for the train data.

###### Evaluation Metric:
The Evaluation metric for this project is Root Mean Squared Logarithmic Error (RMSLE). The RMSLE is calculated as: 
<img src="Screenshot (148).png" style="width:50%;float:left">


<u>We are saving our predictions into a new csv file as "final_result.csv"</u>

## 2. Term Deposit Subscription
Term deposits are a major source of income for a bank.A term deposit is a cash investment held at a financial institution.Our money is 
invested for an agreed rate of interest over a fixed amount of time, or term. we are provided with the client data such as : age of the 
client, their job type, their marital status, etc.Along with the client data, we are also provided with the information of the call such 
as the duration of the call, day and month of the call, etc. Given this information,our task is to predict if the client will subscribe to term deposit.  
 

Our train dataset conatains following variables:
<img src="Screenshot (149).png" style="width:50%;float:left">
<img src="Screenshot (150).png" style="width:50%;float:left">

Our aim is to predict the 'subscribed' variable for the train data.

###### Evaluation Metric:
The Evaluation metric for this is the accuracy of our models.


<u>We are saving our predictions into a new csv file as "my_submission.csv"</u>
