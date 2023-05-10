#BOSTON 311: A DATA-DRIVEN APPROACH TO ENHANCE CITIZEN SERVICES AND QUALITY OF LIFE
This repository contains code for solving two basic probelems:
a.) Can we predict the probability of issue resolution when photographic evidence is submitted, while considering the impact of the source and location of the report?
b.) How can we leverage seasonality patterns from historical data to make accurate predictions of the duration it takes to close a case?
The main file is code.ipynb, which is a python script that loads the necessary data and performs the data cleaning and analysis.

Data
The data used in this analysis is stored in the Link : https://data.boston.gov/dataset/311-service-requests/resource/81a7b022-f8fc-4da5-80e4-b160058ca207. This is the link to the file that contains information on 276723 cases filed in 2022, including their open /close status, demographics, area, date, and various other attributes. The file was obtained from an Boston city government website.

Analysis
The analysis performed in this code involves cleaning the data to make it suitable for modelling. The code highlights how ensembling effect 
improved the result when the analysis was moved from logistic regression to Random Forest.
The code also contains the implementation of multiple linear regression to predict the duration it will take to close a particular case.

Results
The results of the analysis are presented in the presentation file Presentation.pdf .The developed models gave promising result on the test data and could be used for future use to solve:
a.) what are the chances of closure of case within the stipulated deadline provided photographic evidence is available?
b.) How many days it will take for a particluar case to get resolved?

Usage
To run the analysis, simply download the code.ipynb file and run it in Jupyter notebook. 

Credits
The project in this repository has been done by Shahbaz, Gauravi, Maria & Haddy. 
