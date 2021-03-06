﻿Coursera Capstone Project on Finding Venues in Pune City using API 


Q1. What is the aim of this project?

The aim of the project is to identify venues in Pune, India based on their rating and average prices. In this notebook, we will identify various venues in the city of Pune, India, using Foursquare API and Zomato API, to help visitors select the restaurants that suit them the best. 
Whenever a user is visiting a city they start looking for places to visit during their stay. They primarily look for places based on the venue ratings across all venues and the average prices such that the locations fit in their budget. 
Here, we'll identify places that are fit for various individuals based on the information collected from the two APIs and Data Science. Once we have the plot with the venues, any company can launch an application using the same data and suggest users such information. 
Whenever a person searches for a venue in a new city, they’re highly interested in the best places that the city has to offer. The person might want to know how good a given restaurant is or the price range it falls under. This extra information would help decide which venue to choose amongst the many venues in the city. Combining the location of the venues in the city with their price and rating information would surely help visitors in a city make better informed decisions about the places they should visit. This enables any visitor to take a quick glance and decide what place to visit. 


Q2. In what ways will this project be used?

The target audience for such a project is twofold. Firstly, any person who is visiting Pune, India can use the plots and maps from this project to quickly select places that suit their budget and rating preferences. Secondly, a company can use this information to create a website or a mobile application, which is updated on a regular basis, to allow individuals to the city or even expand the same functionality to other places. 
To get location and other information about various venues in Chandigarh, I used two APIs and decided to combine the data from both of them together. Using the Foursquare’s explore API (which gives venues recommendations), I fetched venues up to a range of 4 kilometers from the center of Chandigarh and collected their names, categories and locations (latitude and longitude). Using the name, latitude and longitude values, I used the Zomato search API to fetch venues from its database. This API allows to find venues based on search criteria (usually the name), latitude and longitude values and more. Given that the data from the two APIs did not align completely, I had to use data cleaning to combine the two datasets properly.