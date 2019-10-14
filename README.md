# Google-Analytics-data-analysis-from-an-e-commerce-store


# Introduction

In this project we have analysed a large dataset containing website users data (Google Analytics data) from the Google Merchandise Store, a real ecommerce store. Performed EDA and built a decision tree prediction model to predict if the new visitor will transact or not.

The input dataset contains website users data (Google Analytics data) from Jan 1, 2017 to Jul 31, 2017.
The sample dataset contains obfuscated Google Analytics 360 data from the Google Merchandise Store, a real ecommerce store. The Google Merchandise Store sells Google branded merchandise. The data is typical of what one would see for an ecommerce website. It includes the following kinds of information:

**Traffic source data :** information about where website visitors originate. This includes data about organic traffic, paid search traffic, display traffic, etc.

**Content data:** information about the behavior of users on the site.

**Transactional data:** information about the transactions that occur on the Google Merchandise Store website.


The data obtained is investigated and Exploratory Data Analysis is performed. A decision tree prediction model is built to predict if the new visitor will transact or not.
(When the new visitor visits the website, we get the information about source, medium, campaign, deviceCategory, operatingSystem, city, channelGrouping, pageviews, timeOnSite, bounce, etc).

# Project Description

The datasets used in this project have been chosen from https://storage.googleapis.com/sample_user_behavior_data/sample_user_data.csv

Schema details can be found here: https://support.google.com/analytics/answer/3437719?hl=en


These data is then cleaned, wrangled and then Exploratory Data Analysis is performed using python and its libraries. We identified trends in the transactions performed in relation to users data parameters like Visit Number, Visit date and time, Total time on site, Total page views, bounces, Source and medium of traffic, device category and OS, location etc. Presented findings with relevant statistics and visualizations using the matplotlib and seaborn libraries.

Based on these features, we then build a decision tree model using  python's sklearn library to predict if a new visitor to the website will transact or not.
For this purpose, we split our dataset into train and test sets in 70:30 ratio. The decision tree is built using data from the train set, and is tested using data from the test set to check its accuracy. The model is visualized with the help of different visualization libraries.

# Technologies Used

Python

Libraries: pandas, numpy, matplotlib, seaborn, sklearn, os, Ipython, pydotplus, datetime

Jupyter Notebook

# Results

We gained some insights on the impact of different features like Visit Number, Visit date and time, Total time on site, Total page views, bounces, Source and medium of traffic, device category and OS, location etc on a transaction performed on the website. Using these features a decision tree model is built to predict whether a visitor will transact or not. The decision tree model built has approximately 98% accuracy, which is further optimized by pre-pruning parameters and other attribute selection measures such as entropy.
