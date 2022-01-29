# Tableau Citi Bike Analysis :bike:

## Details About the Challenge
In this challenge, I aggregated data for the 4th quarter of year 2021 found in the [Citi Bike Trip History Logs](https://s3.amazonaws.com/tripdata/index.html) via unions in Tableau to find a couple of interesting conclusions. I built some visualizations for each conclusion and added them to a couple of dashboards. In addition, I created a map that shows the most popular starting and ending stations for the 4th quarter.

## Findings
In this section, you will see what conclusions I've made regarding the Citi Bike data for the months of [October](https://s3.amazonaws.com/tripdata/202110-citibike-tripdata.csv.zip), [November](https://s3.amazonaws.com/tripdata/202111-citibike-tripdata.csv.zip), and [December](https://s3.amazonaws.com/tripdata/202112-citibike-tripdata.csv.zip) of the year 2021.

### ***Number of Monthly Riders Decreased for Q4***
1. I found that the number of riders decreased from October to December regardless of which type of membership the rider held. This is likely due to colder temperatures. Most riders would likely prefer to take a taxi than ride a bike in freezing temperatures.
   - ![image](https://user-images.githubusercontent.com/88349512/151423763-d77de947-929f-40ce-8c63-b9c1bb4913ab.png)
2. These findings show that more riders use the classic bikes versus the electric bikes during this quarter. This is likely due to the cost of electric bikes versus classic bikes.
   - ![image](https://user-images.githubusercontent.com/88349512/151664591-a2f6bcc1-2e47-48dc-aba0-4746fc5277b4.png)

   #### Recommendations
   - We need to look into alternative modes of transportation to meet the needs of the riders during the colder months. This could be enhancing the bikes to include warmers on the handlebars and seat or expanding our brand to include a more enclosed mode of transportation. In addition to looking for alternatives, we should also provide incentives for more riders to use the electric bikes such as coupons/discounts.

### ***Most Popular Places and Times for Rides for Q4***
1. The most popular time to start riding a bike is 5:00pm. This is a good time when people are leaving work and/or going out for the evening.
   - ![image](https://user-images.githubusercontent.com/88349512/151670035-4b515ec7-5687-4b79-841d-b418df4cdd25.png)
   - For casual riders, the most popular time to start riding a bike is 3:00pm. This could be because riders without memberships are likely tourists who are not working during normal hours. With this being the last quarter, it is warmer in the afternoon which makes sight-seeing more appealing.
     - ![image](https://user-images.githubusercontent.com/88349512/151424413-2c032dbc-9cd4-4ae1-b5ab-d68e9c306613.png)
2. The most popular starting stations are W 21st Street & 6th Avenue, E 17th Streety & Broadway, Broadway & E 21st Street, Broadway & E 14th Street, 1st Avenue & E 68th Street, Broadway & W 58th Street, 6th Avenue & W 33rd Street, University Place & E 14th Street, E 13th Street & Avenue A, and Cleveland Place & Spring Street.
   - ![image](https://user-images.githubusercontent.com/88349512/151425122-d6029a63-8701-41ff-ab8d-98783749727f.png)
3. The most popular ending stations are W 21st & 6th Avenue, E 17th Street & Broadway, Broadway & E 21st Street, Broadway & E 14th Street, 6th Avenue & W 33rd Street, 1st Avenue & E 68th Street, University Place & E 14th Street, Broadway & W 58th Street, Cleveland Place & Spring Street, and E 13th Street & Avenue A.
   - ![image](https://user-images.githubusercontent.com/88349512/151426599-5a8757bc-99c0-4030-8623-88b4d29d2520.png)

   #### Recommendations
   - During the visualization process, I had to remove one of the top 10 ending stations because it was "null" meaning the ending station was not reported accurately. We need to investigate why this is happening to have more accurate data. If something is going on with the app to make it less user friendly, our customers will stop using our service. Four out of the top ten starting and ending stations are on Broadway. We should increase our marketing in this area to increase the awareness of our product since this is a popular area for bikers. We could also promote discounts for afternoon and evening rides since more people seem to ride in the evening than in the morning. In addition, we could provide buy one get one half off coupons through hotels to encourage more casual riders since the majority of our casual riders are likely tourists.

## Dashboards
For this project, I created a couple of dashboards to combine some of the visualizations. 
![image](https://user-images.githubusercontent.com/88349512/151669752-a49463b6-72b2-4a34-b273-11c77ad6688c.png)

![image](https://user-images.githubusercontent.com/88349512/151669791-1de82779-beda-4c98-9db3-011ca5e63846.png)

## Maps
I created a couple of dynamic maps to show the most popular starting and ending stations as well as a static map that shows the top 10 starting and ending stations in NYC. With the dynamic maps, you can select which month you'd like to see the popularity of the stations. In addition to choosing the month, the popularity will be shown in size as well as color. The more popular the station is, the bigger it will be and it will show in a darker blue.

#### Most Popular Starting Stations Map
![image](https://user-images.githubusercontent.com/88349512/151669951-8a05a0f7-e408-4372-9d46-181f5a9bd53b.png)

#### Most Popular Ending Stations Map
![image](https://user-images.githubusercontent.com/88349512/151669906-02740938-5230-4109-b6a3-ca0f14dc3978.png)

#### Top 10 Starting and Ending Stations Map
![image](https://user-images.githubusercontent.com/88349512/151669989-092d39b7-44ce-49ad-97ca-c3605bb59ec6.png)

#### Map Findings
The most popular starting and ending stations according to the map are near Broadway which is a very popular tourist area as well where a lot of shops and companies reside. This means that a lot of people that work in that area might use bikes. Additionally, it’s very close to a couple of parks in that area including Union Square and Stuyvesant Park. This is a great area to bike just after work if you work in New York City, or as a tourist to see some of the shops and parks in this area. Probably the biggest reason for its popularity near Broadway and Union Station is because it’s a central location of Manhattan and hosts many subway routes. So when people come into the city via subway, they can hop on a bike, go to where they need to go, and come back to hop back on the subway to go home.

## Story
I also created a story reviewing the above visualizations, dashboards, and maps. Examples of the story sheets are shown below.
![image](https://user-images.githubusercontent.com/88349512/151674800-ce895540-a8a8-478c-929e-540ddcbd0a8b.png)
![image](https://user-images.githubusercontent.com/88349512/151674809-9b45169d-9739-4467-a886-ca5922ee8007.png)
![image](https://user-images.githubusercontent.com/88349512/151674817-052c7e41-69cc-4249-9339-4f00a0639d19.png)

## Tableau
Click this [CitiBike link](https://public.tableau.com/app/profile/jennifer.long2684/viz/CitiBike_16432326735110/StoryCitiBikeAnalysis) to see my Tableau Public file.
