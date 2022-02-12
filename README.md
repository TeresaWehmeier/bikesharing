# Overview
The purpose of this analysis is to examine New York City's Citi Bike Ride-sharing data to determine whether a similar business model would be profitable in Des Moines, IA. Citi Bike makes historical data available to the public, and August 2019 rides were used to develop the analysis. The analysis focuses on the number of bike rides, who uses the bikes, and where the highest usage areas are during the month examined in the dataset.

## About Citi Bike
Citi Bike is the nation's largetst bike share program, with 20,000 bikes and 1,300 stations across Manhattan, Brooklyn, Queens, the Bronx and Jersey City. The service is designed for quick trips (less than 50 minutes). Pricing ranges from $3.50 for a single 30 minute ride, up to an annual membership (subscriber) for unlimited 45-minute rides at $15.42 per month.

## Technologies Used in Analysis
The dataset was imported as a DataFrame in Jupyter Notebook, and the trip duration was converted to a datetime format to better analyze the bike usage in time formats. The Jupyter file is located <a href="NYC_Citibike_Challenge.ipynb">here</a>. Tableau Public was used to develop analysis and a dashboard story for this project. The tableau story can be viewed here: <a href="https://public.tableau.com/app/profile/teresa.l.wehmeier/viz/NYCCitiBike-SharingChallenge/NYCCitibikeStory?publish=yes">NYC Citi Bike Story</a>.

# Results
There were minimum requirements for this analysis defined by the project team, which include seven visualizations that analyze:
- The length of time that bikes are checked out for all riders and genders
<img src="Images/nyc_citibike_story_checkout_times.png" width="40%" height="20%">

- The number of bike trips for all riders and genders for each hour of each day of the week
<img src="Images/nyc_citibike_story_when.png" width="40%" height="20%">

- The number of bike trips for each type of user and gender for each day of the week
<img src="Images/nyc_citibike_story_who_served.png" width="40%" height="20%">

In addition, there were some key points during the analysis that are important to examine in detail, when and where specific types of users (subscriber or customer) access bikes, and for what purpose. A street map was developed to help with this analysis that marks locations on the map where bikes are checked out and by which user type, along with a point of interest layer to identify key locations for these bike checkouts.
<img src="Images/nyc_citibike_story_where.png" width="40%" height="20%">

