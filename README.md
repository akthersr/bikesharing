# Bikesharing

## Overview of the project

Two tourists from Des Moines,Iowa was fascinated by the NYC Citi Bike sharing service during their last summer trip to New York City and plan to launch a similar business in their hometown. But before analysis, we must keep in mind that New York City is well-organized before Des Moines. Where, Manhattan very densely populated and concede high traffic tourist areas to run this kind of expansion service for tourists and daily commuters. So our goal is to convince the potential investors that a bike-sharing program in Des Moines is a solid business proposal.

## Purpose

The main purpose of this analysis is to create effective visualizations from the Citi Bike data, by using Tableau Public to impress potential investors, to solidify the proposal.In this visualization, we are going to use the data from August month, because there is more traffic during the summer months.

The visualization of the story can be found here.

## Resources

-Data sources:201908-citibike-tripdata.csv,bike_data_challenge.

-Tools:Tableau Public,Jupyter Notebook.

## Results

### Tripduration

Using Python and Pandas functions, we convert the "tripduration" column from an integer to a datetime datatype and create a dataframe from the data (201908-citibike-tripdata.csv) source.

![](https://github.com/akthersr/bikesharing/blob/main/tripduration.png)


### User and Gender BreakDown

The total number of bike trips recorded during the month of August are 2,344,224. Majority customers of NYC bike-sharing service,are annual subscribers in comperission with customers(short-term riders). Among them, a total of 1,900,359 customers are annual subscribers (81%).

![](https://github.com/akthersr/bikesharing/blob/main/user%20type%201.png)  ![]()

Current subscribers of Citi Bike are dominantly Male, which was almost 65% of the total users. And the number of female users is 25% .

### Average tripduration

The below image shows that,the younger riders tend to use the bikes for longer periods of time. The trend shows that, the later the birth year, the longer the ride duration.  

![](https://github.com/akthersr/bikesharing/blob/main/average%20trip%20duration.png)

### August Peak Hours

The following bar chart shows that, the top riding hours during August in New York City are 5:00 p.m to 7:00 p.m and the ideal time for bike maintaince and redistribution of bikes, are between 2:00 a.m. to 5:00 a.m. According to the analysis we found that,this was the least active time for bike riding. From the chart, we can see bike usage in peak during morning rush hours and end of the office hours.

![](https://github.com/akthersr/bikesharing/blob/main/august%20pick%20.png)

### Top Starting Locations

The below image shows that most trips originate in Lower Manhattan, this area have more bike rides due to the heavy number of tourists.We can visulize from the map that the bike trips originating in the business district,Lower Manhattan. The darkness of the green color and the size of the circles indicate the number of trips originated at those points.On the otherhand, in the less densely populated neibourhoods,the bike usage rate is less than Downtown Manhattan.

![](https://github.com/akthersr/bikesharing/blob/main/top%20starting%20locations.png)

![]()

### Top Ending Locations

The destinations of most trips are same stations where the riders are started their trips. The top ending locations are in the tourist and busy areas,here we can see in Manhattan.

![](https://github.com/akthersr/bikesharing/blob/main/top%20ending%20locations1.png)

### Checkout times for users

The checkout time for most users are less than 20 minutes. The cohort shows, the trips are very short. 

![]()

### Checkout times by gender

According to the data, about 2.3 million people use the Citi Bike service, among them Male users use 3X then Female users.The number of users for both Male and Female are almost same. The trip durations for both gender are very short,but Male takes slightly longer trips than Female.

![]()

### Trips by Weekday per Hour

Most trips occur on weekdays during rush hours from 7 a.m. to 9 a.m. and 5 p.m to 7 p.m. On weekends, most trips occur in between 10 a.m and 5 p.m.The trend shows Saturday is also a busy day for bike users during weekends. In weekdays,the busiest time to rent bike for going to office and coming back home from work. An interesting finding is the low usage of bike during Wednesday's end-of-commute.

![]()

### Trips by Gender

The heatmap shows breakdown of the number of bike trips by gender for each hour of each day of the week. The pattern indicates that Males dominantely rent bikes more than Females over the course of each week. The below image show clear peak times in deep red which are to and from work.

![]()

### User Trips by Gender by Weekday 

In this visualization, we create a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype. The trend shows that the current subscribers to Citi Bike are dominently Male,but the customers are evenly distributed for both genders. The dark blue area represents the peak time for both genders by weekday and weekends.

![]()

### Summary

In conclusion, bikesharing services like CitiBike service are popular in bussiness areas(like NYC). NYC has a high density of residents who live in the city,known for towering office buildings, densely packed residential skyscrapers and entertainment venues. Most users base are Male subscribers,provides regular bussiness to tne program.It evident from the analysis that most users use this service for commute to work in weekdays and main usage seems to be in morning & evening commute times.The bikes usage is very frequent in commercial areas,some bikes are used more than others and needs more survicing.

  This analysis gives us an idea of what Des Moines bike share program could look like, using data from NYC in August. The key points to note for Des Moines program are, high traffic tourist and office areas like downtown Manhattan would be served.For Des Moines, if there is good advertisement,promotional offers and proper marketing,the number of customers,subscribers could increase. As a result,this could increase tourism revenue across the city.
  
### Future Analysis

- Trips starting and ending locations during morning and evening rush hour times on a week,comparison to other locations.
- We can create a visualization map in most populer routes by starting and ending stations.






