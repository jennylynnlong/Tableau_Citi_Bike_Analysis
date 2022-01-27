# Tableau CitiBike Analysis :bike:

## Details About the Challenge
In this challenge, I aggregated data for the 4th quarter of year 2021 found in the [Citi Bike Trip History Logs](https://s3.amazonaws.com/tripdata/index.html) via unions in Tableau to find a couple of interesting conclusions. I built some visualizations for each conclusion and added them to a couple of dashboards. In addition, I created a map that shows the most popular starting and ending stations for the 4th quarter.

## Findings
In this section, you will see what conclusions I've made regarding the Citi Bike data for the months of [October](https://s3.amazonaws.com/tripdata/202110-citibike-tripdata.csv.zip), [November](https://s3.amazonaws.com/tripdata/202111-citibike-tripdata.csv.zip), and [December](https://s3.amazonaws.com/tripdata/202112-citibike-tripdata.csv.zip) of the year 2021.

### ***Number of Monthly Riders for Q4***
1. I found that the number of riders decreased from October to December regardless of which type of membership the rider held. This is likely due to colder temperatures. Most riders would likely prefer to take a taxi than ride a bike in freezing temperatures.
   - ![image](https://user-images.githubusercontent.com/88349512/151423763-d77de947-929f-40ce-8c63-b9c1bb4913ab.png)
2. These findings show that more riders use the classic bikes versus the electric bikes during this quarter. This is likely due to the cost of electric bikes versus classic bikes.
   - ![image](https://user-images.githubusercontent.com/88349512/151423890-1c68868a-e89d-46f4-8041-1d0762cf20c5.png)

   #### Recommendations
   - We need to look into alternative modes of transportation to meet the needs of the riders during the colder months. This could be enhancing the bikes to include warmers on the handlebars and seat or expanding our brand to include a more enclosed mode of transportation. In addition to looking for alternatives, we should also provide incentives for more riders to use the electric bikes such as coupons/discounts.

### ***Most Popular Places and Times for Rides for Q4***
1. The most popular time to start riding a bike is 5:00pm. This is a good time when people are leaving work and/or going out for the evening.
   - ![image](https://user-images.githubusercontent.com/88349512/151424003-e5364d4b-cd42-45d8-a71d-23932e85f4c4.png)
   - For casual riders, the most popular time to start riding a bike is 3:00pm. This could be because riders without memberships are likely tourists who are not working during normal hours. With this being the last quarter, it is warmer in the afternoon which makes sight-seeing more appealing.
     - ![image](https://user-images.githubusercontent.com/88349512/151424413-2c032dbc-9cd4-4ae1-b5ab-d68e9c306613.png)
2. The most popular starting stations are W 21st Street & 6th Avenue, E 17th Streety & Broadway, Broadway & E 21st Street, Broadway & E 14th Street, 1st Avenue & E 68th Street, Broadway & W 58th Street, 6th Avenue & W 33rd Street, University Place & E 14th Street, E 13th Street & Avenue A, and Cleveland Place & Spring Street.
   - ![image](https://user-images.githubusercontent.com/88349512/151425122-d6029a63-8701-41ff-ab8d-98783749727f.png)
3. The most popular ending stations are W 21st & 6th Avenue, E 17th Street & Broadway, Broadway & E 21st Street, Broadway & E 14th Street, 6th Avenue & W 33rd Street, 1st Avenue & E 68th Street, University Place & E 14th Street, Broadway & W 58th Street, Cleveland Place & Spring Street, and E 13th Street & Avenue A.
   - ![image](https://user-images.githubusercontent.com/88349512/151426599-5a8757bc-99c0-4030-8623-88b4d29d2520.png)

   #### Recommendations
   - During the visualization process, I had to remove one of the top 10 ending stations because it was "null" meaning the ending station was not reported accurately. We need to investigate why this is happening to have more accurate data. If something is going on with the app to make it less user friendly, our customers will stop using our service. Four out of the top ten starting and ending stations are on Broadway. We should increase our marketing in this area to increase the awareness of our product since this is a popular area for bikers. We could also promote discounts for afternoon and evening rides since more people seem to ride in the evening than in the morning. In addition, we could provide buy one get one half off coupons through hotels to encourage more casual riders since the majority of our casual riders are likely tourists.
