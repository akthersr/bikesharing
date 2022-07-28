# Bikesharing

## Overview of the project

Two tourists from Des Moines,Iowa was fascinated by the NYC Citi Bike sharing service during their last summer trip to New York City and plan to launch a similar business in their hometown. But before analysis, we must keep in mind that New York City is well organized before Des Moines. Where, Manhattan is very densely populated and concede high traffic tourist areas to run this kind of expansion service for tourists and daily commuters. So our goal is to convince the potential investors that a bike-sharing program in Des Moines is a solid business proposal.

## Purpose

The main purpose of this analysis is to create effective visualizations from the Citi Bike data, by using Tableau Public to impress potential investors, to solidify the proposal.In this visualization, we are going to use the data from August month, because there is likely more traffic during the summer months.

The visualization of the story can be found here.

## Resources

-Data sources:201908-citibike-tripdata.csv,bike_data_challenge.

-Tools:Tableau Public,Jupyter Notebook.

## Results

### Tripduration

Using Python and Pandas functions, we convert the "tripduration" column from an integer to a datetime datatype and create a dataframe from the data(201908-citibike-tripdata.csv) source.

![]()


### User and Gender BreakDown

The total number of bike trips recorded during the month of August are 2,344,224. Majority customers of NYC bike-sharing service,are annual subscribers in comperission with customers(short-term riders). Among them,a total of 1,900,359 customers are annual subscribers(81%).

![]()  ![]()

Current subscribers of Citi Bike are dominantly Male, which was almost 65% of the total users. And the number of female users are 25% .

### Average tripduration

The below image shows that,the younger riders tend to use the bikes for longer periods of time. The trend shows that, the later the birth year, the longer the ride duration.  

![]()

### August Peak Hours

The following bar chart shows that, the top riding hours during August in New York City are 5:00 p.m to 7:00 p.m and the ideal time for bike maintaince are between 
2:00 a.m. to 5:00 a.m. According to the analysis we found that,this was the least active time for bike riding.

![]()

### Starting points




