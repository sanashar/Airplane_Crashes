# Airplane Crashes
![October]()

# Overview 
Airplane transportation is an exciting and brilliant invention. Even though they are being flown all around the globe, but flying comes with many risks. The dataset I am using is available through [data.world](https://data.world/data-society/airplane-crashes#_=_). In this homework I will use kmeans as the clustering algorithm to create 5 clusters, by predicting words from the text and extracting labels from the Airplane Crash data. Experimental results have shown that kmeans prediction performance is good for 2 out of 5 clusters.
# Project Goal
From fatal crash accident info of Airplane Crashes, using cluster and visual analysis, can we detect the highest survival passenger in crash by operator? Are the crashes decreasing or increasing by years?

Finding the survival trend by operator and classifying them into different segments based on clustering of the text summary beforehand can help the aviation engineers to take necessary care and precautions which decreases the casualties of airplane. Can we detect groups to help them sort the main reasons for crashes through clusters is my machine learning problem.
# Motivation & Background
The fact that instances of the plane crash are not particularly normal, they are very fatal. The most recent crash was on the evening of August 7, 2020, Air India Express Flight 1344 crashed with 190 people on board during a botched landing attempt, killing 18 passenger and 150 injured. Even though the aviation giants took many precautions to control these fatalities, incidents are still being reported. The objective is to cluster these fatalities into several different segments based on text summary. These datasets involving accidents and fatalities are important for data scientists to investigate because with enough data, we may one day be able to prevent them.

# Repository Navigation 

Table of Contents -

Technical Notebook               : [PlaneCrash](https://github.com/sanashar/breast_power_project1/tree/main/notebooks)

Summary Report       : [Report](https://github.com/sanashar/breast_power_project1/tree/main/reports)

# Data Summary
The Airplane Crash dataset is available through [data.world](https://data.world/data-society/airplane-crashes#_=_) that has the crash data from 1908 to 2009. It has 5268 rows and 13 columns and dtype as float and object. It includes all aviation accidents reported in the United States, its territories and possessions, and in international waters. This is a great dataset to help us sol ve our business problem, by exploring this dataset I hope it will teach us how to improve the quality and safety of traveling by Airplane.

Attributes include -

1. Date
2. Time
3. Location
4. Operator
5. Flight #
6. Route
7. Type
8. Registration
9. cn/In
10. Aboard
11. Fatalities
12. Ground
13. Summary

# Project Info & Software Requirements
DATA 602 Homework 2- Sana Sharma

Languages    : Python 2.7

Tools/IDE    : Google Colabratory

Libraries    : pandas, matplotlib, statsmodels, minibatch kmeans, kmeans, seaborn
