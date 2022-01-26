# Tableau CitiBike Analysis :bike:

## Details About the Challenge
In this challenge, I aggregated data for the 4th quarter of year 2021 found in the [Citi Bike Trip History Logs](https://s3.amazonaws.com/tripdata/index.html) via unions in Tableau to find a couple of interesting conclusions. I built some visualizations for each conclusion and added them to a couple of dashboards. In addition, I created a map ....

## Findings
In this section, you will see what conclusions I've made regarding the Citi Bike data for the months of [October](https://s3.amazonaws.com/tripdata/202110-citibike-tripdata.csv.zip), [November](https://s3.amazonaws.com/tripdata/202111-citibike-tripdata.csv.zip), and [December](https://s3.amazonaws.com/tripdata/202112-citibike-tripdata.csv.zip) of the year 2021.

### ***Number of Monthly Riders for Q4***
1. I found that the number of riders decreased from October to December regardless of which type of membership the rider held. This is likely due to colder temperatures. Most riders would likely prefer to take a taxi than ride a bike in freezing temperatures.
2. These findings show that more riders use the classic bikes versus the electric bikes during this quarter. This is likely due to the cost of electric bikes versus classic bikes.

   #### Recommendations
   - We need to look into alternative modes of transportation to meet the needs of the riders during the colder months. This could be enhancing the bikes to include warmers on the handlebars and seat or expanding our brand to include a more enclosed mode of transportation. In addition to looking for alternatives, we should also provide incentives for more riders to use the electric bikes such as coupons/discounts.

### ***Most Popular Places and Times for Rides for Q4***
1. The most popular time to start riding a bike is 5:00pm. This is a good time when people are leaving work and/or going out for the evening.
2. The most popular starting stations are ...
3. The most popular ending stations are...

   #### Recommendations
   - During the visualization process, I had to remove one of the top 10 ending stations because it was "null" meaning the ending station was not reported accurately. We need to investigate why this is happening to have more accurate data. If something is going on with the app to make it less user friendly, our customers will stop using our service. Four out of the top ten starting and ending stations are on Broadway. We should increase our marketing in this area to increase the awareness of our product since this is a popular area for bikers. We could also promote discounts for evening rides since more people seem to ride in the evening than in the morning. In addition, we could provide buy one get one half off coupons for existing evening riders to encourage rides in the morning.
