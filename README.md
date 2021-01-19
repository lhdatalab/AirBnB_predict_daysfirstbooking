# AirBnB predict days until first booking

Machine learning using python and AirBnB booking data
 
 airbnb_customer_booking_ML.html - http://lhdatalab.github.io/airbnb_customer_booking_ML.html 

AirBnB data for predicting the country of first destination is readily
available online (Kaggle). Can this same data be used to define/solve 
other problems or create new opportunities?

One idea for this project is to create a seperate project using the same data. 

<b>Note: This analysis does not include any 2020 data.</b>

Project Days until revenue collected (days until first booking).

It takes around 4 days before a user first books on AirBnB. When session data is included the MAD (median absolute deviation) decreases drastically from 7 to 0.13. However the test score is lower than the train score which shows there is a variance problem. In this case the model can be improve by having more data.

The main analytics (machine learning) observations from this project are:

    1. Missing values can skew the results

    2. Finding a way to change the number of variables (bias) and 
    observations (variance) with limited project resources

    3. Choice of model and metric using nonlinear algorithms

    4. How to handle unexpected results
        i. Transform output variable
        ii. Parameter tuning
