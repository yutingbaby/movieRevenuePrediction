# Project 2: TMDB Box Office Prediction: Predict Movie Revenue
Programming Language: R

## Overview:
Nowadays where movies made nearly $12 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? Or the genres? These are the questions we would like to answer. 

For this project, we studied metadata on over 7,000 past films and applied EDA and predictive analysis. Some of our variables are numeric, and some are texts. The goal of our project is to find out the important factors that would influence a movie’s revenue, and build a predictive model to forecast a movie’s revenue. 
We tried several techniques including random forest, text mining, extreme gradient boosting, clustering, neural network, and SVM. Our best model (xgboost with text mining) reached a rmsle of 2.1.

## Data Cleaning and EDA
Please read tmdb_prediction_dataCleaning&EDA.Rmd
* Exploratatry Data Analysis: used Matplotlib
* Data Cleaning
  * Extract texts from JSON format using regular expression
  * Fixed date format from unusual date format
  
## Further Data Preparation and Predictive Model Building
Please read tmdb_FinalAnalysis.html	Final Analysis Code Part II
* Dummy Encoding
* Predictive Model: XGBoost


For more analysis details, please read the project on my website (https://yutinggong.github.io/).

