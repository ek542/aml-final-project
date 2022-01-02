# Analyzing NYC stop-and-frisk using supervised learning techniques 

This repo contains the code and data for our final CS 5785 Applied Machine Learning final project (Fall 2021). This project focuses on analyzing NYC's stop-and-frisk data for 2015-2019, after the 2013 ruling that stop-and-frisk violated the Fourth Amedment. We compare various Machine Learning classification techniques - Logistic Regression, Support Vector Machines, and Random Forest Classifier - to predict the likelihood of a weapon being found, given a certain set of neighborhood, suspect, and time factors, and also identify which factors are most important in the decision to conduct stop-and-frisk. A use case of this model would be a screening app that the police can use to assess pedestrians they are observing and thinking of potentially stopping before they decide to stop them. An accurate predictive model will thus help reduce the number of ‘unnecessary stops.’   

Libraries needed to run the core code: numpy, pandas, matplotlib, sklearn

Experimental libraries include prince, inflect
