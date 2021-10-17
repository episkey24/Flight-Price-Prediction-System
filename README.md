## Flight-Price-Prediction-System
UCS757 - Building Innovative Systems. <br />
Project - 2 <br />
[Live Link](https://ucs757-p2-fps-101803201.herokuapp.com/) 
### Overview
A machine learning web app that predicts the price of the flight based on several features. The application is built using Flask and deployed on Heroku platform. The model is built using Random forest regressor with a R2 score of 81.38% after going through Hyper Parameter tuning(RandomizedSearchCV). <br />
## Screenshots
![Home Page](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(88).png) <br />
![Predictions](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(90).png)
## Python Libraries Used
- Numpy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- Missingno
## Exploratory Data Analysis
- Airline v/s Price
![pic](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(389).png) <br />
- Month v/s Price
![pic1](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(394).png) <br />
- Source v/s Price
![pic2](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(392).png) <br />
- Destination v/s Price
![pic3](https://github.com/episkey24/Flight-Price-Prediction-System/blob/main/img/Screenshot%20(393).png) <br />
## Model Selection
I have tried 6 regressor models of which random forest regressor performed really well.
Here are the test scores for the models:
- Random Forest - 83.24%
- KNN - 52.2%
- Ridge regressor - 58.6%
- Lasso regressor - 60.7%
- Decision Tree regressor - 73.9%
- XGB regressor - 83.03% 
Random forest regressor model and XGB regressor model performed really well compared to other algorithms.
## Project Workflow
## Dataset Info
- The dataset is taken from Kaggle - (https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)
- Dataset contains 10683 rows and 11 columns
- Features - Airline , Date of Journey, Source, destination, Route, Departure time, Arrival time, Duration, Total Stops, Additional info
## Novelty
- Price of flight ticket varies abruptly and it becomes hectic for a user to decide on different deals. A flight fare prediction model will help travellers with the optimal time to plan their travel and understand the trends in the airline industry.
## Future Scope
- Work on larger data
- Improve front end web design
- Scalability
