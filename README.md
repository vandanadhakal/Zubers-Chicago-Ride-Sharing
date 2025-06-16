# Zubers Chicago Ride Sharing
Analyzed ride-sharing data from Zuber to uncover passenger preferences and assess the impact of weather on ride frequency. Processed and queried data by joining four relational tables, utilizing subqueries, aggregation, and slicing techniques to extract meaningful insights.

## Objective
Analyze data from competitors to understand passenger preferences and the impact of weather on ride/ride frequency.

## Summary
Explored Zuber, a ride-sharing company in Chicago to understand the passenger preferences, impact of weather on ride frequency and duration in popular neighborhood.
➔	Methods/Techniques: Processed data by joining 4 data tables, used subqueries, aggregation and slicing techniques.
➔	Results: Identified top-performing taxi companies and neighborhoods. Underscored how adverse weather conditions affected trip durations and number of trips. Rides from Loop neighborhood to O'Hare International Airport on a Saturday had 5:1 ratio of rides during good to bad weather condition.
➔	Recommendations: Results provide insights to the company that weather conditions has high impact on customer’s preferences, indicating customers inclination to use ride-sharing services on a good weather condition. Thus, highlighting the need to have a contingency plan like promotions on adverse weather conditions.


### Project Description
The database used in this project consists of four tables: **Trips**, **Cabs**, **Weather_Records**, and **Neighborhoods**.
The first step involved conducting **Exploratory Data Analysis (EDA)** to identify the most popular taxi companies based on the **number of rides** provided.
The next phase focused on determining **whether and how ride durations from the Loop to O’Hare International Airport** varied on **rainy and stormy Saturdays** compared to **other weather conditions**.


### Database Schema
A database with info on taxi rides in Chicago:
`neighborhoods` table: data on city neighborhoods
`cabs` table: data on taxis
`trips` table: data on rides
`weather_records` table: data on weather

The Databse Scheme:
<img src="https://github.com/vandanadhakal/Zubers-Chicago-Ride-Sharing/blob/main/Table%20Scheme.png">


