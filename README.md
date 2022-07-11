# Module 14 challenge - Bikesharing business analysis

## Overview of the statistical analysis
After discovering a bikesharing business in NY, we are being asked to analyze the available data. After completing this analysis, we will be able to understand the different metrics behind this business: customers, their habits, behaviors, and main locations. After the analysis is complete, we should be able to determine if a similar business in Des Moines has a good chance of being successful. 

## Results
The visualizations we have built will be fundamental to explain our analysis. You can find the whole story here, in my [Tableau Public Profile for Module 14](https://public.tableau.com/app/profile/abraham.ramos6560/viz/ChallengeModule14_16568846470470/Ourcustomersandtheirhabits)

Let's analyze the story...

### Visualization 1 - Checkout times for users

![vis_01](/imgs/vis_01.png)

This graph is showing the duration for trips made by customers. We can see the peak of the graph is at 146k users, with a trip duration of five minutes. Generally speaking, we can observe the majority of trips are taking between 1 to 60 minutes. From this, We can conclude most of the trips are of very short duration. This is telling us our users have well definied ending points.

### Visualization 2 - Checkout times by gender

![vis_02](/imgs/vis_02.png)

This visualization is similar to visualization 1, but broken down by gender. The bahavior is basically the same, for all three data categories. Most of the trips are taking five to ten minutes. Also, we can see that most of the trips are done by men, meaning that most of our customers belong to that group.

### Visualization 3 - Trips by weekday for each hour

![vis_03](/imgs/vis_03.png)

This visualization is helping us to understand how much trips are completed by hour. We can see a pattern here. From Monday to Friday, we can see most of the trips are done at the same times. From 7am  to 9 am and 5 pm to 7 pm. These are working hours. This means our customers are considering bike as mean of transportation. 
During the weekends, we can see a similar behavior on Saturdays and Sundays. We have an evenly distrubution of trips from 10 am to 7 pm. Saturdays are busier than Sundays. We can conclude that our customers are also using bike as a mean of transportation during their weekend plans. 

### Visualization 4 - Trips by gender

![vis_04](/imgs/vis_04.png)

This is similar to visualization 3, but broken down by gender. This confirms our conclusions so far. Most of our customers are men. All our customers are traveling on well defined times from Monday to Friday (they are trying to reach their work places). On weekends, Saturday is a good day for the business. Busy hours are from 10 am to 7 pm.

### Visualization 5 - User trips by gender

![vis_05](/imgs/vis_05.png)

This one is similar to visualization 3 and 4, but it is segragating data by user type: "Customer" or "Subscriber". The "Customer" segment is showing a flat behavior. It is very hard to say what are the days with more activity. This is different for the "Subscriber" segment. Behavior between women and men is very similar. Thursday is the day with the highest activity. 

### Extra visualizations 6 and 7 - Starting and Ending points

 Top starting points

 ![vis_06](/imgs/vis_06.png)

 Top ending points

![vis_07](/imgs/vis_07.png)

These visualizations are showing the top starting and ending points for all trips. Taking this as a starting point, we can start thinking why these stations are the most popular. Are they close to a train station? close to any other popular spots such as restaurants or any other entertainment centers? It grabs my attention that the top starting point and the top ending point are the same. 

### Extra visualization 8 - Customers age groups

![vis_08](/imgs/vis_08.png)

This visualization is showing the different age groups for all our customers. Our largest customer groups were born in the 80s and 90s. This is important to know the preferences of our customers. It is also important to know their priorities and the stage of their lives. 

## Summary and conclusion
After building and analyzing these visualizations, some of our key findings are:
1. Number of customer and number of suscribers
2. Number of female customers Vs. number of male customers
3. Hours of the day with most trips
4. Days with most trips
5. Trips by Gender
6. Stations with most trips (starting and ending points)

Although it is true these metrics show the behavior of the business for New York city, we can get some good conclusions that can apply for any major city. We should ellaborate some answers for questions like:
1. Customer gender: Women Vs Men - We have learned that our largest customer base are men, but why? Is it because biking is not a convenient mean of transportation for women? is it because of security? Does biking represents a high risk transportation method for women?
2. Trips hours and duration: For business days, most of the trips take place during well defined hours. For weekends, we can see an even distribution, being Sundays the days with the lowest activity. 
3. Subscribers Vs Customers - The analysis has confirmed most of our users are subscribers, which makes sense. Why the customer group has not made the decision to get a subscription? Are they not frequent users? do they find the cost too high? This is a good start. Finding answer to these questions may help us to increase our subscriber base.

To dig deeper into this analysis, we ma create different visualizations, depending on the available data:
1. **Complaints** - What are the biggest issues our customers are facing. To solve this, it will be important to classify the data and create categories for the complaints.
2. **Months with more activity** - The data is already there. We just need to create one single source file for a whole year. This is important because we would be able to determine the months with the highest acitvity. This can help us to plan maintenance calendars and procurement calendars. 
3. **Subscription dates** - How many of our subscribers are returning? How many of them are first time subscribers? It is important to determine this. Having a high rate of retuning customer is paramount to keep a good customer base. 

Getting answers to all questions will provide a good idea of the components that we should be considering when opening a bike sharing business. Asking the right questions will help us to take good decisions. 