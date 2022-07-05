# Airbnb-Listing-Review-Analysis
![image](https://user-images.githubusercontent.com/82467138/177321466-527d0e08-53dd-4555-b0c4-b9df4ed809cd.png)
* 📁 (https://www.mavenanalytics.io/data-playground?search=airbnb)
* 🖥️ (https://public.tableau.com/app/profile/marcellino.paskah.nichora/viz/BI-AirbnbListingReviewAnalysis/Story1)

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
<br>
#### Level of Competition
![image](https://user-images.githubusercontent.com/82467138/177358067-ac427909-7ae9-4c9e-a6f8-2208a23ca3b1.png)
We compare the total capacities each city has with the total number of visitors respectively. It can be seen that Rome offers great opportunities for the potential investor because the supply of accommodation for 800k visitors in Rome is still low compared to others. As seen in the down-right chart, the level of "big players" in Rome is remain low compared to other cities which is a good sign for small businesses to list their properties in Rome.

#### Comparing Prices
![image](https://user-images.githubusercontent.com/82467138/177360404-8a1f8167-1c06-4577-b064-5b51f402048a.png)
A private room has the highest average price compared to other categories. It indicates to the potential owner that a private room has a higher chance of generating higher revenue. Meanwhile, based on the city, New York has the highest average price followed by Rio de Janeiro and Sydney.

#### Discussion
Overall, Airbnb as a company needs to increase their marketing activity because the growth of listings each year are decreasing significantly. With the world is getting recover from the pandemic, the tourism activities are expected to rise again in 2022 which will help Airbnb to recover. 
For those who want to list their property in Airbnb here is our recommendation:
* Looking at the level of competition, Rome and Mexico City are great cities to list your property. But if you're a "bigger player", New York is also a good option to pick.
* Pricetag to rent a property is very competitive so keep in mind to watch your competitor pricetag. 
* Europe generate the highest revenue among other continent. It may be wise to invest in Europe because the environment for tourism is well established which will support your property rent business.
