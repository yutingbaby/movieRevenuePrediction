# Project 2: TMDB Box Office Prediction: Predict Movie Revenue
Programming Language: R

## Overview:
Nowadays where movies made nearly $12 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? Or the genres? These are the questions we would like to answer. 

For this project, we studied metadata on over 7,000 past films and applied EDA and predictive analysis. The goal of our project is to find out the important factors that would influence a movie’s revenue, and build a predictive model to forecast a movie’s revenue. 
We tried several techniques including random forest, text mining, extreme gradient boosting, clustering, neural network, and SVM. Our best model (xgboost with text mining) reached a rmsle of 2.1.

## Data Cleaning and EDA
See: tmdb_prediction_dataCleaning&EDA.Rmd
* Exploratatry Data Analysis on key variables: used Matplotlib
* Data Cleaning
  * Extract useful text information from JSON format using regular expression
  * Fixed data types including using math calculation to get the right date from a unusual date format
 
## Text Mining
See [Rmarkdown] (https://htmlpreview.github.io/?https://raw.githubusercontent.com/yutinggong/Project2movieRevenuePrediction/master/Final.textmining.EDA.html)
* Sentiment Analysis of variable "Overview" 
* Keyword Extration from "Overview", kept the top 20 words from TFIDF result

## Predictive Model Building
Please read https://htmlpreview.github.io/?https://github.com/yutinggong/Project2movieRevenuePrediction/blob/master/tmdb_FinalAnalysis.html
* Dummy Encoding
* Predictive Model: XGBoost
* Other experimented models: please read https://raw.githubusercontent.com/yutinggong/Project2movieRevenuePrediction/master/Working%20R.model.html


For more analysis details, please read the project on my website (https://yutinggong.github.io/).

