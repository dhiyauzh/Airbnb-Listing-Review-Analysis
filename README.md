# Airbnb-Listing-Review-Analysis
![image](https://user-images.githubusercontent.com/82467138/177321466-527d0e08-53dd-4555-b0c4-b9df4ed809cd.png)

## Introduction
This is a group project of 4 people including me as the final project to pass the Business intelligence course. We chose a public dataset that contains listings and reviews from Airbnb which was retrieved from maven analytics (...). We are assigned to find business insights from a public dataset using Tableau as a data analytics tool. Airbnb Listing & Review dataset contains data for 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews. 
We wanted to produce valuable information for potential investor who wants to list their property on the Airbnb platform. We wanted to give suggestions on which is the best city to build properties, what type of building, and which market is suitable for each type of investor.

## Data Pre-processing
First, we create a relationship between Listings.csv and Reviews.csv with a called "listing_id" which is stated in both files so we can use each table in our analysis. We didn't use either join or union because we wanted to explore these data without eliminating any column and view the table separately. Column "price" was listed in local currency as respective cities. We decided to convert all of the values in this column to US dollars (USD) so we had a better understanding of the information.

## Results
#### Listing Growth in 10 Big Cities
![image](https://user-images.githubusercontent.com/82467138/177352268-a4a3cdcd-ba01-4fb0-a84f-956818a0a7d0.png)
Here is the preview of listing growth from the foundation of Airbnb in 2008 until 2021. The overall number of listings are decreasing when it reached its peak growth in 2015. Pandemic also takes part in an extremely decreasing number of new listings because people tend to stay at home during this crisis. These numbers are projected to continue to drop until 2023. Paris is leading in total capacities and total listings among 10 big cities which indicates them as one of the centers of tourism in Europe. The majority of owners are renting the entire place of their property when they listed their property on Airbnb.
<br>
#### Level of Competition
![image](https://user-images.githubusercontent.com/82467138/177358067-ac427909-7ae9-4c9e-a6f8-2208a23ca3b1.png)
