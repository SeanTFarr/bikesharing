
<img src= 'images\des-moines.png'>

---
# Objective of project
The purpose of this project is to analyze the data from Citi Bike NYC to sell the idea that a Citi Bike in Des Moines would be a good investment. After downloading a csv file from the Citi Bike System Data page, Pandas was used to change the datatype of the "tripduration" column from an integer to a datetime datatype. Then loaded the Python file into a new csv file. Using Tableau, the data was then processed to pull out pertinent information into visulalizations for a better view of the Citi Bike operation.

To see the whole data story, click the link to [my Tableau dashboard](https://public.tableau.com/app/profile/sean.farr2471/viz/Citi-Bike-Analysis_16380479507120/CitiBikeAnalysis)

---
# Analysis
### Bike checkout times by gender:
<img src='images\Gender_line_and_pie.png'>
This was the first indicator that males used the bikes more often than females. The large amount of shorter duration bike trips, most at around 6 minutes, indicate that the riders didn't often go very far, which is fitting for travelling into and out of a densly populated area.


### User types:

<img src='images\usertype_pie.png'>

There were far more subscribers than regular customers. This indicates that the locals utilize the system frequently.

### Heatmaps of the weekday usage:
<img src='images\Heatmaps.png'>
These heatmaps show the usage being at its highest volume Monday - Friday and the highest time frames being from 7-9 a.m. and  5-7 p.m.. In a quick look at trips by gender, again you see that males were more likely to use the bikes.

### The Station Volume:
<img src='images\stations.png'>

In these maps, each station, both start and end stations, are indicated by a circle. The larger the circle the larger the volume. You can see that the highest concentration of stations and the largest volumes are in the heart of the city.
### Trip Hours:
<img src='images\start-stop_hours.png'>
The above bar charts show the number of trips per hour daily and includes both the subscriber and the regular customer.
<img src='images\customers.png'>
By selecting only the customer, you can see that the usage is in line with what one would expect from tourism. there is a subtle climb in volume that starts mid-morning and then starts to decline late in the afternoon. 
<img src='images\subscribers.png'>
With the subscriber box checked, you can see the spikes in time at the beginning of the workday and the end of the workday

### The Ages of the Riders
<img src='images\ages.png'>
Beyond the usage difference in the genders, there was another interesting stat that came out of this analysis, the age of the riders. Most of the riders where in their 30's.

---

# Summary

## How it will work for Des Moines
Whereas New York City is 39 times larger than Des Moines, there are some similarities that would indicate the bike sharing would work.
1. Both have a metropolitan area that is much larger than the city residnetial population. New York City's population(8.3 million in 2019) is 43% of the NYC Metro area(19.2 million in 2109). Des Moines city population(214,237 in 2019) is only 30% of the Des Moines Metro area(699,292 in 2019). This would have a large number of locals traveling into and out of the city
2. Age range between 18 and 65 are about the same percentage of the population. New York has 57.2% and Des Moines has 57.3% of their polulations that are in the age range that would use the bikes.
3. Average travel time to work. For NYC it is statistically 37.7 minutes. For Des Moines it is around 20.6 minutes. As indicated in the analysis, there were a lot of shorter trips which is possibly due to the density of the downtown area. With a shorter travel to work time combined with the ease and cost effectiveness of riding the bike versus waiting on a cab and/or waiting in traffic(think about the fuel!), it becomes a simple choice.

## What could also be looked at
Using this current dataset, we could look at the frequency of use for each bike to see if there are bikes that are getting used more than others, which could turn into a maintenance issue. There could also be an investigation into where subscribers start and end their rides versus where customers start and end.

For further investigation beyond the dataset, Miami has a Citi Bike operation that would be worth looking into. It is a much smaller city than New York, so an secondary analysis could give additional information to make a final decision.
It would also be worth the time to look into price per ride and cost per bike for both purchase and maintenance.



