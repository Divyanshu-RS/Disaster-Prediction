# Disaster-prediction
The goal of this project is to forecast any potential flood or drought risks that may result from rainfall at a specific location in India. Flood and drought are two connected natural disasters that, despite their initial appearance of being independent, are greatly influenced and determined by the amount of rainfall in a certain area. There are several characteristics linked to the rainfall that will be expressed in millimeters. As an illustration, the term "rainfall" can refer to any of the following: daily, monthly, seasonal, or yearly rainfall, all of which reflect and influence different biological phenomena.



## Need.
It is evident that both drought and floods are significant natural disasters that impact a significant portion of the population each year. Therefore, in this case, if a system or, for a larger user base, an app can be developed that analyzes rainfall data in a person's area and can alert the user in the event of possible flooding, the user may take appropriate action to minimize harm to themselves and their property. The Indian Meteorological Department may utilize the same technique to organize and handle similar situations and ensure that the disaster affects fewer people.



## Process
So how are we going to do it? We are going to use machine learning, deep learning and statistical learning theory to train our model to predict the calamity. We have got our data from Indian Govt Website (https://data.gov.in/resources/district-rainfall-normal-mm-monthly-seasonal-and-annual-data-period-1951-2000), it contains the monthly, annual and seasonal rainfall data of each state and their major district of India. The data is 50 years, from 1951-2000. Also we are getting instantaneous data of rainfall (visually data after each day) from Indian Meteorological Department (http://hydro.imd.gov.in/hydrometweb/(S(4py24b55cjhnute4evewhr55))/landing.aspx).The data looks like this.

- Phase 1:

<p>Simple Prediction using the above stated model. Independent analysis of the data( independent in the sense that rainfall in Uttrakhand will not have any effect on the people living in Delhi)</p>

- Phase 2:

Correlational Analysis: <br>
<p>It is quite possible that a heavy rainfall in North can bring flood in all the areas which are in the vicinity of that area, and it is also important to analyse that part. So after making the basic model, we'll try to incorporate this aspect also in our model.</p>


## Methodology
To develop precise forecasts, we will use past flood or drought events to determine the class labels or the threshold for each. To increase the flexibility and robustness of our model, we will employ supervised, unsupervised, parametric, and non-parametric learning techniques.

After that, we're going to create an Android app for the similar UI experience. The Android app will utilize the geolocation API to determine the user's position and retrieve rainfall data from the Meteorological Department. An algorithm will then be performed on the back end to estimate the likelihood of any localized disasters, and the user will be notified in real time.



## Summary
1.Training the model on previous data.

2.Taking USER's Location from the APP.

3.Running the algo at back-end.

4.Predicting the chances of flood.

5.Notifying the User.


## Conclusion
I think that this approach will be very helpful to many individuals and the government in anticipating the calamity and lessening its effects on the general public. People won't have to endure the same suffering year after year thanks to this, and society will be slightly improved.


