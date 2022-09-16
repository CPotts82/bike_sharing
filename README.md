# bike_sharing
## Analysis Overview
The purpose of the analysis is to study the CitiBike Data from New York City's bikeshare program to help investors decide if a bike sharing program could be successful in Des Moines, Iowa. The analysis studies how the bike share program works in New York City to see how it could possibly transition over to  Des Moines. One of the potential investors has requested a bike trip analysis to gain more insight into this proposed program. 
### Background 

![General Info](https://user-images.githubusercontent.com/106348899/190530581-21a9ff59-9d23-4a25-b6ff-b4b5b88dd0e7.png)

This dashboard shows multiple visualizations that represent important background pieces of information for this analysis.  The analysis focused on the citibike data taken from the month of August. At the top of the visualization it shows the total number of bike rides for the month of August to be 2,344,224.  The bar graph underneath August bike trips shows the peak hours during the month.  Overall, the busiest hours were during business hours with peak times in the morning and evening when people would be commuting to and from work. 

At the bottom of the dashboard there are two graphs: a pie chart and a line graph.  These charts visualize the different types of users in the bike share program.  There are subscribers and customers. Subscribers have a subscription to the program and pay monthy or yearly.  Customers are not necessarily consistent users and pay per use of the bikes. The line chart shows the number of users for the month of August by the age of user, and further filtered by the type of user, customer or subscriber. This graph shows a big jump in users for customers born in 1969 and jump for subscribers born at this time as well. (This is a bit odd and should go through additional analysis to find the cause of this jump.) There is also a steady increase in the number of subscribers born from 1975 to 1991. 

## Resources
VS Code, Tableau Public, 201908_citibike_tripdata.csv, nyc_bike_trip.csv

** The full Tableau Story can be found at:
[link to dashboard](https://public.tableau.com/app/profile/clara.potts/viz/CitiBikeChallenge_16632661232750/NYCCitiBikeAnalysis?publish=yes)

## Results
Each of the following visualizations shows a piece of the bike trip analysis requested by the investor. Underneath each graph is an explanation and the results of the specific piece of the overall anlaysis. 

![Checkout Times](https://user-images.githubusercontent.com/106348899/190530723-17bfbb6c-3348-4d70-bba9-2764ba1de94a.png)

Checkout Times for Users shows the trip durations for all users, both subscriber and customers throughout the month of August. This chart can be filtered by the number of hours per trip duration.  The majority of bike trips are less than 1 hour and more specifically approximately 5 minutes long. There is a sharp increase in the amount of trips that range from 1 minute to 6 minutes. After the 6 minute peak, there is a sharp then steady decline in the length of bicycle trips.  Most trips are under an hour though there are a sufficient number of bike trips that are over 1 and 2 hours long.  


![Checkout Tiimes Gender](https://user-images.githubusercontent.com/106348899/190530864-bccf7384-b451-4501-9bc8-818d0c5cd319.png)

This next chart is almost identical to the previous one with the exception that it includes a breakdown of gender of the users in the trip duration analysis. It is very apparent from this chart that males are the primary users of the NYC bike share program. 

![Trips by Weekday Hour](https://user-images.githubusercontent.com/106348899/190530973-a2d1bcf3-ff94-48dc-aab5-f09018ef610f.png)

This next visualization is a heatmap that showcases number of bike trips at any given hour on each day of the week for the month of August. The chart clearly shows that the busiest times are Monday through Friday mornings and evenings when most people are commuting for work.  These would most likely be subscribers that utilize this bike share program to get to and from work.  The weekends also show a busy time from about 9 am to 7 pm.  These users would most likely be customers but also some subscribers that are using the bikes to visit tourist attractions, restaurants, and go on other social outings. 

![Trips by Gender](https://user-images.githubusercontent.com/106348899/190531179-85c8cd9f-cb24-44b2-8c34-f035cb3ca6c1.png)

This heatmap is very similar to the previous one, it shows the number of bike trips for each hour of each weekday in August. The difference here is that it is filtered by gender. The first heat block shows female users and it is apparent that Monday through Friday morning and evening work commutes are busiest.  Females are also using the bikes more frequently on Saturdays from about 9 am to 4 pm and Sundays from about 10 am to 4 pm. Males heavily utilize these bikes for the work communtes Monday through Friday. Saturdays are also very busy for male bike riders from about 9 am to 7 pm and then on Sundays from about 9 am to 7 pm as well. There is also a heat block with 'unknown' gender (will explain what this could mean with the next graph) that shows a heavier use on Saturdays from mid-morning to evening. There is an uptick in usage as the week progresses starting on Thursdays and continuing through Sundays suggesting that these users may be utilizing the bikes for more tourist and social attractions. 

![Gender Weekday Trips](https://user-images.githubusercontent.com/106348899/190531306-691dd748-1ed8-424c-bd57-e11ac6869394.png)

This final visualization is a heatmap that breaks downs bike trips by day of the week, gender and finally by the type of user; customer or subscriber. The majority of males and females that use this program are subscribers.  Males make up the majority of subscribers. It is interesting to note that the 'Unknown' gender is predominately made up of more customers than subscribers. The 'Unknown' gender users mostly use these bikes on Saturdays and Sundays showing that they are most likely tourists or city dwellers that occasionally use bikes for social outings.


## Summary

### Results Summary
This analysis was done on New York City bike share data but there are multiple aspects that could correspond to Des Moines, Iowa.  Data was analyzed for the month of August which is still a really nice month for people to ride bikes on their daily commute as well as visit the tourist attractions and social events in New York and Des Moines alike. Des Moines has a very dense metro area similar to New York City and therefore the trip durations would likely be similar. People would subscribe to this service in order to take a short bike ride from a metro hub to their work destination or their residence in the city. The only difference I see here is that there would be less weekend activity in Des Moines compared to New York City simply due to the amount of tourist attractions and events held in New York versus Des Moines. The peak hours from the New York analysis would likely carry over to peak hours of bike use in Des Moines as well. The amount of trips by weekday per hour would be similar between the two cities because most subscribers go to and from work around the same time as people in New York City.  Weekend activity would be heavier in Des Moines around the same times as New York's weekend activity, but there would be less overall weekend activity as mentioned before. The other difference I see between New York and Des Moines would potentially be the amount of customers. The customers would be less in Des Moines simply because the tourist attractions here cannot compare to those of New York City. 

### Suggestions

