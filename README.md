# My data science portfolio
The purpose of this repository is to give an idea to the reader about my technical skill level on data science applications .

These projects were part of my learning process from university lectures of my M.Sc. program and other various sources. At some point, I decided to polish and upgrade them for portfolio purposes, and I prepared them as easy to follow and digest.

# [Project 1: Forecasting Store Sales Through Time Series Analysis.](https://github.com/ildeniz/ML-2022-003-Forecasting_Store_Sales_Through_Time_Series_Analysis) 
This project is influenced by [Rossman Store Sales competition](https://www.kaggle.com/competitions/rossmann-store-sales) that held in Kaggle and ran from 30th of September to 12th of December, 2015.
The data set is obtained from [Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/data)

* Developed a hybrid model to predict the 1115 Rossmann stores' average daily sales for the next 60 days to give them useful insights to make more accurate budgeting process and ease financial decision making.
* Engineered features through given data sets to eliminate trend, seasonality and cycle components to make the time series stationary and the predictions accurate.
* Root Mean Square Percentage Error: 0.1774

Improvements TODO:
  * Optimize hybrid model of Linear and Extreme Gradient Boosting Regressors using GridsearchCV to reach the best model.
  * Built a client facing API using flask/django/etc.

![](/Images/Actual_vs_Prediction_comparison.png )

# [Project 2: Anime Recommendation System](https://github.com/ildeniz/Anime_Recommendation_System)  
As a fellow anime fan, I wanted to make an anime recommendation system as a portfolio project.  
To achieve this, I created a web scraper by using Jikan (時間) REST API to scrap 2334 TV anime productions data between 2010-2022 and 86269 individual users' data from the most used online anime and manga catalogue [myanimelist[DOT]net](https://myanimelist.net/).

The project is still in progress. Until now:
* Created web scrapers by using Jikan (時間) REST API to scrap anime and user information from myanimelist.
* Scraped 2333 anime TV productions between 2010-2022 from myanimelist using python and the created scraper.
* Scraped 86269 individual users' data.

TODO:
* Data cleaning
* EDA
* Model building (clustering)

![](/images/image.png)

# [Project 3: Glass Classification [**This project is being updated**]](https://github.com/ildeniz/ML-2022-001-Glass_classification) 

The purpose of this project is to define the type of a glass depending on the given features. 

The motivation behind the glass classification is given by the contributor as;
>The study of classification of types of glass was motivated by
criminological investigation. At the scene of the crime, the glass left
can be used as evidence…if it is correctly identified!

The data set used in this work is obtained from;
- https://archive.ics.uci.edu/ml/datasets/Glass+Identification

![](/images/image.png)



