##Advanced Business Analytics 
Team Members
Amith Sivarai and Priyanka Sabnani



#### Explaroratory Data Analysis 
#### Exploring Cars 

## Type of Final Project

### Exploring Used Car Sales and Features 
We used python Jupyter notebook for our analysis, modelling,  Data Visualization and created various graphs and summaries out of it. 
We have markdown code chunks with simple explanations about the steps and graphs of our projects. 

## Project Summary : 
For a private buyer or seller who are new to the used-car market, a common confusion is about what to be expected. Therefore, this project attempts to provide a used-car evaluation service based on the on-line listing information.
The objective of the project is to discuss the features of used-car with regard to its influence on the market price. Based on such analysis, a model for price prediction could be constructed in order to provide a real-time used-car evaluation service. The final product takes features (vehicle type, make, year, Engine Fuel Type, Engine HP Driven Type , Transmission, Vehicle Style, MPG .) of a used-car as input and output a prediction of price. Moreover, it should be capable of producing an interval prediction as price range, and it should be able to handle missing features so that the user can make a query even when they are not clear about certain feature. As a more ambitious attempt, we tried a regression model and PCA Principal Component Models – Reduced similar dimensions, in order to ease the data we reduced similar dimensions that adds the same value to the data. 

The data used in the following analysis is taken from Edmunds. It contains 10,000 observations of 16 features. We attempted to experiments with all the techniques learned in the class, tried our hands on cleaning and using functions later we see a detailed visualization. And in last we have our models and PCA. 


Data Sources:https://www.edmunds.com/industry-center/data/consumer-vehicle-purchase-intent-by-manufacturer.html

Project Folder have a jupyter notebook and an excel that contains the data along with the read.me file. 

The libraries used for this projects are :
import pandas as pd 
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import scipy as sp

We have inserted a R markdown Chunk at every grpah with explanation of what we are trying to analyze. 
Phase 1 - We read and understand the data and try few functions, played around with data like dropping columns and renaming or checking the stats. 
We normalized the data -Checked missing values, removed missing values. We also detected outliers through boxplot and removed them with IQR. 

Phase 2-
Data Visualization: 
We understood the variables and their relationship with each other in depth. The main Variable is price we made numerous graphs to understand the price of the car dependent on all features the car. 
We developed a detailed Correlation Matrix and Regression Model in the last along with some unsupervised learning techniques.  

Youtube link for presentation: https://youtu.be/5MiuaSN34oU

