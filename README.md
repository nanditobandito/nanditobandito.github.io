#  Capstone Project
## Predicting Student Performance to Forecast University Enrollment
## Fernando A Zambrano
## The George Washington University

Not all universities have dedicated registrar departments, nor access to specific software to keep track of student enrollment to forecast future enrollment.  The ability to develop reliable student forecast brings multiple benefits in regard to both university finances and student investment. This study explores prior student data from the Institution Tecnologico de Chihuahua (ITCH), with the intent to develop such forecast models. This is achieved through an ensemble of different predictive models such as a Support Vector Machine (SVM) binary classification, ordinary least squares linear regression (OLS), and Holt-Winter Exponential Smoothing. 

This repository contains all the necessary data and tools to thouroughly analyz student data of ITCH

Files in the Data Folder hold the raw data from ITCH in Excel formats

Files in teh JupyterCodes conatin 3 Jupyter notebooks. 
There is one dedicated to data cleaning, translating from Spanish to English, and preprocessing the raw data.
The EDA notebook performs Exploratoty Data Analysis on the data
The FinalModel notebook performs binary calssification, OLS, and Holt-Winters method to predict pass or fails of students of the spring semester in 2019.

There is keynot presentation that gives a quick overview of the project labled Capstone Presentation. There are hyper links to individaul Tableau dashboards within the keynote presentation. Otherwise the TableauViz folder contains an html document where all the dashboards reside, the data used to create the dashboards, as well as the tableau notbooks.

Finally there is a full report of the project titled Predicting Student Performance to Forecast University Enrollment.
