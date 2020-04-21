# Social network analysis

A graph is constructed using Airbnb listings and reviews. Each reviewer has an id


In this age of unprecedented connectivity, they say every person on earth is only 5 connections away from each other. Showcased in this notebook is a general framework for examining these connections, and analyzing the degrees of seperation between nodes in a social network.

Examples of nodes and their connectivity include:
 - Forums on reddit, connected to other subreddits by the users who post in them
 - Groups on Facebook, connected to other groups by the users who frequent them
 - Locations on a map, connected to other locations by people who visit them
 
The latter is of particular interest at the time this code was written, as Google and Apple are currently working together to build an app that determines users' potential risk for having came into contact with covid-19.



##### Networks of airbnb listings connected by shared reviewers 

Given a collection of airbnb listings, and the reviewers who have reportedly stayed there, we can predict the way a virus would spread to other airbnb listings in that city by connecting each node to every other node sharing at least 1 reviewer within a given timeframe.
