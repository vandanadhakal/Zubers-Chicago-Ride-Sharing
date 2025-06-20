# Zuber Chicago Ride Sharing Database
Analyzed ride-sharing data from Zuber to uncover passenger preferences and assess the impact of weather on ride frequency. Processed and queried data by joining relational tables, utilizing subqueries, aggregation, and slicing techniques to extract meaningful insights.

<img src="https://github.com/vandanadhakal/Zubers-Chicago-Ride-Sharing/blob/main/images.jpeg" width="450" height="350">

## Objective
Analyze data from competitors to **understand passenger preferences** and the **impact of weather on ride/ride frequency**.

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

### Process
This project is developed using PostgreSQL and involved the use of **JOINs**, **subqueries**, **CASE statements**, and other essential SQL clauses.

The analysis began by identifying the most popular taxi companies and calculating the total number of trips they provided during a representative week. To achieve this, the **Cabs** table is left joined with the **Trips** table to determine the total ride count for each cab company.

The second part of the project explored the **impact of weather on ride volume** from the Loop neighborhood to O’Hare International Airport. Specifically, it compared the number of rides taken on **rainy and stormy Saturdays** versus more favorable weather. For this, the **Weather_Records** table is joined with the **Trips** table to capture weather conditions and classify them as either *“Good”* or *“Bad"*. Ride data for trips from the Loop to O’Hare on Saturdays is then extracted and analyzed in the context of these weather categories. Further, the total count of Good to Bad weather condition rides is determined.

The file with project SQL query can be found here: [`Zuber's Ride Sharing Project`](https://drive.google.com/file/d/1uKR7Zf2dsxrH19v1qutM0sndfqbU-dKf/view?usp=share_link)

### Conclusions
1. Flash Cab and Taxi Affiliation Services emerged as the two most popular taxi companies.

2. Together, they accounted for 23% of the total rides during the representative week analyzed.

3. On Saturdays, rides from the Loop neighborhood to O’Hare International Airport showed a stark contrast: 888 rides during good weather vs. 180 rides during bad weather.

4. The data suggests that customers are more likely to use ride-sharing services in favorable weather conditions.

5. Offering promotions or discounts during inclement weather could be an effective strategy to increase ride volume for taxi companies.

### Assumption
1. A representative time frame is selected to analyze and identify the top-performing taxi companies, with the assumption that this period is reflective of overall trends in the full dataset.

2. Rain and storm conditions are classified as *“Bad”* weather, while all other weather conditions are categorized as *“Good”*.



