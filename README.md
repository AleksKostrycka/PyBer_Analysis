# **PyBer Analysis Challange**
## **Analysis Overview**
The purpose of this analysis was to create a summary of the ride-sharing data by city type. Using the skills learned in this Module the intent was to create a DataFrame of the ride-sharing data by city type, then using Pandas and Matplotlib create a multi-line graph that shows the weekly fares for each city type. 
## **Results**
The purpose of Deliverable #1 was to complete a ride-sharing summary DataFrame by city type. Using the Jupyter Notebook we were able to create this DataFrame by grouping information into three categories, or types of cities, Rural, Suburban and Urban. The summary DataFrame includes the following information for each of the city categories.
* Total rides 
* Total drivers 
* Total fares 
* Average fare per ride 
* Average fare per driver

![This is an image](https://github.com/AleksKostrycka/PyBer_Analysis/blob/main/Deliverable%201%20Image.png?raw=true)

The purpose of Deliverable #2 was to complete a multiple line graph of total fares for each city type. This was completed through a series of steps which include a new DataFrame which showed the total fares by each category and by the date the fare occured. The we create a pivot table that allowed us to recongigure and group the total fares that happened on a specific date and indicated in which cateogy of cities the fares occured. This way we were able to see the total fares for each of the three categoires by date that the fare occured. We then narrowed our data set to a specific period from January to April only, recongifured the DataFrame to show total fares for each category per week, and finally created a multiple line graph to visualize the information. The resulting visualization is below:

![This is an image](https://github.com/AleksKostrycka/PyBer_Analysis/blob/main/Deliverable%202%20image.png?raw=true)

### **Analysis of Results**
By studing the above visualization it is clear that Urban cities have significantly higher total fares compared to the other two types, Rural and Suburban. This does not come as a shockng conclusion to the analysis as cities usually have a higher number of ride-share users, as well as ride-share drivers with in its population. A significantly lower number of people have their own cars in urban ares which can be due to multiple factors: affordability, parking restrictions availablity and price, as well as the need for individuals to have their own cars, ie. distance between home and work. In the Rural and Suburban areas where the population is more spreadout, owning a car is a necessity to get around, therefore ride-sharing is also a less frequent mode of transporation. Based on the analysis completed in Deliverable 1 it is clear that the ubran areas have a higher number of total rides, higher number of drivers, and much higher total fares (as explained above). However, urban areas also have the lowest avg. fare per ride, as well as the lowest avg fare per driver. This can be analyzed and explained by a variety of factors such as, the distance driven in Rural and Suburban areas. The miles per ride is higher drives up the fare per ride as well as the fare per driver total dollars. In urban areas the distances between locations is much shorter which will result in lower miles, lower fares and lower fares per driver. However there is a much bigger demand in ubran areas for ride-sharing therefore the number of rides and total drivers is much higher and theavg fare per ride and avg fare per driver is naturally lower. 
