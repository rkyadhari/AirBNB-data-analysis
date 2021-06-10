# AirBNB-data-analysis
Udacity Data Scientist NanoDegree Program - Project 1

**Installation and Libraries**
As part of Udacity's Data Scientist NanoDegree Program, we are provided with Seattle AirBNB's data for our analysis.
Reference: https://www.kaggle.com/airbnb/seattle
The dataset consists of three files namely 'listings.csv', 'review.csv', and 'calendar.csv'

The standard libraries installed for the project:

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import matplotlib.pyplot as plt

from sklearn.metrics import mean_squared_error

from sklearn.preprocessing import StandardScaler

from sklearn.model_selection import train_test_split

from sklearn.metrics import confusion_matrix

from sklearn.linear_model import LinearRegression

from sklearn.tree import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

from sklearn.ensemble import RandomForestRegressor

from sklearn.metrics import r2_score

**Project Motivation**

We attempt to answer the following questions with the intention to help future visitors to Seattle.

1. How are the listings distributed by various property types?
2. What is the average price of listings by neighborhood?
3. What are the most expensive months to travel to Seattle in terms of reservation prices?
4. What are the main factors that influence the price of the listings?

**Steps:**

In order to answer the above business questions, the high level steps are mentioned below

1.Analysis of 3 files namely Listings,Review, and Calendar

2.Clean up data files for NAN valus and apply appropriate imputing stragegies

3.Draw inferences via charts,graphs, and heat maps on the varous attributes and features available in the data files.

4.Use Ramdom Forest Regressior and Linear Regrssion models against training and test data and choose the best fit model

5.Derive the most important fetaures for predicting the price of the listings

**File Descriptions**

![GitHub File Structure](https://user-images.githubusercontent.com/85522420/121435130-3d116f80-c933-11eb-9427-d779d4682046.png)


**Acknowledgement**

I would like to acknowledge and thank AirBNB for making the dataset public to be used for our project and also Udacity to give students of DataScientist NanoDegree program an opportunity to work with this dataset.

**Results**

By answering the above questions, I hope to have certain data points handy for visitors to look into before thay make their next reservation and stay at one of Seattle's AriBNB locations.
![neighborhood_Cleansed](https://user-images.githubusercontent.com/85522420/121436343-426fb980-c935-11eb-8575-b2111ecf2120.png)
![Price Distribution By Month of Travel](https://user-images.githubusercontent.com/85522420/121436364-4a2f5e00-c935-11eb-8b62-279516cb8425.png)

