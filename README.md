# Bike_Sharing

## Project Overview
Bike sharing is growing all over the United States. Among the cities participating in the system are New York, Chicago and Washington, D.C. But if you thought this sort of sustainable-minded movement were just a fad confined to the metropoles of the world, you'd be wrong. Enter stage left: Des Moines, Iowa. 

This report aims to inform investors of the potential footprint and success of a bike sharing program in the midwest, specifically in Des Moines, Iowa. Using data from a bike sharing business in New York City, I have created visualizations and suggestions about market viability in the midwest. 

Points of discussion:

* Spatial analysis: Checkout locations
* Temporal analysis: Checkout times, weekly usage & ride duration 
* Demographic analysis: Users by subscription type & gender 
* Bike maintenance schedule

Visualizations:

* Symbol maps
* Pie charts
* Heat maps
* 

#### Resources used
* Data Source: https://ride.citibikenyc.com/system-data
    * Data used for the month of August, 2019
* Software: Tableau Public Desktop (version 2022.1.0); Jupyter Notebook

## Results

First, we break down users by gender group. This shows overwhelmingly that nearly 75% of the users are male:

![deliverable_1 7](https://user-images.githubusercontent.com/87148145/166127111-47b0befd-ebb0-4504-a5bb-2611c335d384.PNG)

All users fall into one of two groups: subscribed or unsubscribed. 

Here, we can see the subscriber data in context of each week. There are two takeaways with this data. First, subscribers are most active during weekdays, likely a result of work commutes. The other notable feature is the uptick of unknown rides on the weekends, regardless of gender:

![deliverable_1 5](https://user-images.githubusercontent.com/87148145/166127151-c0243d92-104b-408d-aad7-e6ee7d46648d.PNG)

Taking a more granular look at this usage data, we can see highest traffic occurs at 8am and 5-6pm. This not only adds to our suspicion that these are commuters, but also suggests that bike maintenance should occur outside of these 'peak' hours:

![deliverable_1 3](https://user-images.githubusercontent.com/87148145/166127253-2c4474ee-069e-42f9-900c-ce305448a701.PNG)

This appears to be equal across genders:

![deliverable_1 4](https://user-images.githubusercontent.com/87148145/166127179-752e9c24-99ea-48e7-8918-910501025c5c.PNG)

Most single rides only last about 10 minutes, likely accounting for work commutes:

![deliverable_1 2](https://user-images.githubusercontent.com/87148145/166127343-bb41a6f0-d1fd-414a-bcff-576becbaefb0.PNG)

Again, this is nearly equal across genders:

![deliverable_1 1](https://user-images.githubusercontent.com/87148145/166127395-ec56793f-0d3a-4980-9d42-832eafe78add.PNG)

Finally, a spatial analysis helps to tie the above data points together. The heat map below shows the highest-visited checkout locations as larger, darker circles. 

![deliverable_1 6](https://user-images.githubusercontent.com/87148145/166127138-412d7f44-f09f-46b2-ab78-a1c849e1b959.PNG)


## Summary
Our analysis suggests there is a significant market for New York employees to subscribe for commuting. However, to implement a similar program in the city of Des Moines would require additional analysis and acute attention in planning. We suggest a follow-up geographic analysis of the highest-visited checkout sites in New York City that cross-references the proximity of subscribers' employers. This may inform optimal placement of bike stations. Such a visualization could also imply centralized location(s) for bike maintenance shops. Finally, we suggest an analysis that uses the checkout location heat map across subscribed and unsubscribed groups. This would further inform advertising and marketing campaigns, e.g. "Tour the city!" vs. "The commute that gets you in shape!"
