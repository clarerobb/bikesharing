# NYC Citi Bike Anaylsis with Tableau

## Overview
This project visualizes the data from Citi Bike in New York City in August 2019 with Tableau to determine the viablity of a bike-sharing business in Des Moines, Iowa. 

## Resources
**Data Source:** [Citi Bike Data](https://ride.citibikenyc.com/system-data) <br>
**Software:** Python 3.7.13, Tableau Public 2022.2.1

## Results

#### Customer Base
In August 2019, more than 1,900,000 of Citi Bike's users in New York City were long-term annual subscribers as opposed to the short-term customers.<br>
![Screen Shot 2022-09-10 at 6 09 13 PM](https://user-images.githubusercontent.com/106405775/189504727-852dd613-5e8f-47ea-b68c-d8bf42aa2d2b.png)<br>

#### Hours of Use
Bikes are more freqquently rented between 5:00pm - 7:00pm. The morning rush hour (7:00am-8:00am) is also a busy time for Citi Bikes. During these times, it is important to have most bikes in circulation.<br>
Bikes are rented the least between 2:00am - 4:00am. This time frame would be the best to service any bikes needing repairs. <br>
![Screen Shot 2022-09-10 at 6 19 59 PM](https://user-images.githubusercontent.com/106405775/189504966-edefe994-3521-49f2-a2f3-5ab8ee8b8a0d.png)

#### Trip durations
The vast majority of trips are under an hour, specifically under 30 minutes. There is a sharp drop off around the 30-40 minute mark. This implies most trips are taken short distances. <br>
![Screen Shot 2022-09-10 at 6 31 34 PM](https://user-images.githubusercontent.com/106405775/189505223-347f73e2-3305-4401-8d1b-02a59505c4eb.png)

#### Trip Durations by Gender
Users identifying as male make up a significant portion of Citi Bike's users.<br>
![Screen Shot 2022-09-10 at 6 35 46 PM](https://user-images.githubusercontent.com/106405775/189505294-0079c070-93e4-4986-b2e7-f576fedec69b.png)

#### Weekday Hours of Use
This heat map reinforces the previous hours of use chart by showing that morning and evening rush hours during the week are the most popular times to rent a bike. On Fridays, the evening rush hour appears to begin earlier than the other workdays, which would conincide with summer Fridays. Converely, on Saturdays and Sundays, bikes are more frequently rented from 10:00am - 5:00pm. <br>
![Screen Shot 2022-09-10 at 6 45 41 PM](https://user-images.githubusercontent.com/106405775/189505435-5f226a11-fb51-4e80-bb06-6255b6777ed4.png)

#### Gender Breakdown for Hours of Use
Again, we see that males are more likely to be renting bikes on during the morning and evening commutes. <br>
![Screen Shot 2022-09-10 at 6 51 18 PM](https://user-images.githubusercontent.com/106405775/189505534-ad3f1ec6-2cfe-43af-bfe3-6753d1d7a1ae.png)

#### User Trips by Gender
Similar to previous charts, we see that male subscribers are renting Citi Bikes more frequently than short-term customers and female users. <br>
![Screen Shot 2022-09-10 at 6 56 03 PM](https://user-images.githubusercontent.com/106405775/189505645-63d5f152-f132-4e0a-8229-8c1435de5469.png)

#### The full Tableau story can be seen [here](https://public.tableau.com/app/profile/clare.robbins/viz/NYCCitibikeStory_16628475197900/NYCCitibikeStory).

## Summary
Bikesharing services are popular in New York City in August. The vast majority of users are annual subscribers and identify as male. With more than 80% of users being long-term annual subscribers, the company has a regular income. Bikes are rented most frequently during the weekday rush hours implying that users are using this as an alternative to public transportation. 

With this dataset, I would also pursue the following:
- Compare the start and ending locations during the rush hour commutes to display the flow of traffic between neighborhoods. 
- Compare the trip durations during the week as opposed to the weekend to determine if users are taking longer trips on the weekend. 
