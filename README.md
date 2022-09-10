# bikesharing

## Purpose
A potential investor has requested a bike trip analysis to solidify a proposal to start a bikesharing business similar to New York City's CitiBike in Des Moines, IA.

For this repository I took the original csv file and converted the tripduration column (which was originally in integer format) to datetime format in order to be able to accurately visualize the length of time bikes were checked out.  Using this updated column and other columns in the dataset, I used Tableau to create a story of visualizations that would be helpful in determining what time bikes are frequently checked out and where they are returned. This information from New York City can be used as a starting point in a new bikesharing business in Des Moines to determine the least customer-disruptive times to maintain equipment (an important part of a solid business plan). Also included is a breakdown of gender and use.  This can be used by marketing for attempting to increase interest with the underrepresented portion of the population. 

- **Language**: Python (Pandas library)
- **Software**: Tableau, Jupyter Notebook
- **Data Source**: csv file

## Results
### [Link to Tableau Story](https://public.tableau.com/app/profile/mandy.glynn/viz/InsightsintoCitiBike/InsightsintoCitiBike)
Click the link above to view the story in its entirety on Tableau.  A breakdown of each slide is included below.

### Gender and User by Weekday
![User_Trips_by_Gender_by_Weekday](https://user-images.githubusercontent.com/102555125/189431998-2a2fb14a-19cf-45ec-906d-d7bf76a3619e.png)
This dashboard includes a heat map of Customer Type and Gender and which days of the week they use the service most.  It can be filtered by customer type and by gender. "Customer" refers to a customer not signed up for a regular subscription service and "Subscriber" refers to a customer who has a subscription agreement. 

### All Use per Hour
![All_Use_by_Hour](https://user-images.githubusercontent.com/102555125/189432085-ba9ba054-793f-4360-a199-e281228517c1.png)
This visualization shows all users and what times of the day are most popular for using the bikeshare service.

### Gender Use per Hour
![Trips_by_Gender_by_Hour](https://user-images.githubusercontent.com/102555125/189432033-2c966f7e-df6a-4d41-890a-8694af82f486.png)
This visualization breaks down the previous heatmap into genders and their most popular times of usage.

### Starttime vs Stoptime
![Starttime_vs_Stoptime](https://user-images.githubusercontent.com/102555125/189432054-f507064f-083b-4e18-bdfd-3f546bb58729.png)
This dashboard compares the start times of a bike ride to the stoptimes over each hour of the day.

### Duration of Checkouts
![Bike_Checkout_Times](https://user-images.githubusercontent.com/102555125/189432095-2379deaf-196e-4261-9899-1fe9c11862d5.png)
This dashboard compared the checkout times for all users to the checkout times by gender.  It is filterable by the duration of the ride and by gender (for the bottom line graph).

### Filterable Usage by Day and Hour
![Hour_Use_by_Weekday](https://user-images.githubusercontent.com/102555125/189432075-76cbffe2-274d-4b8d-b8c0-3ab323a331ee.png)
This bar graph will be the most use to someone trying to determine when to maintain equipment.  It shows the count of bikes used by starttime and by day of the week.  It can be filtered to show one or multiple days of the week at once and the hour of starttime.  It is color coded to show high usage, medium usage, and low usage.

### End Destination for Bikes
![End_Destination](https://user-images.githubusercontent.com/102555125/189432064-7eb74ec9-5f30-4b14-a7c3-a5a9ceaf2006.png)
This geographical map of New York shows the most popular end destinations for bikes. More popular areas are represented by a larger circle marker and by color.

## Summary
Given that Des Moines has moved up from #51 (in 2016) to #38 (in 2018) in ranking for the best bike cities in America [according to Bicycle Magazine and Bike Iowa](https://www.bikeiowa.com/Feature/1711/des-moines-ranking-in-the-best-bike-cities-in-america), a bikeshare has the possibility to be a profitable and useful business to the residents and visitors there as continued improvements are made to the city's infrastructure to accommodate bike riders and commuters.

The best times for bike maintenance are from Midnight to 5am all days of the week as the bike usage falls dramatically during this time.  Other convenient times are Monday-Wednesday from 10am - 3pm. The worst time for maintenance falls in the typical office travel hours from 7am - 9am and from 5pm - 8pm.

Also noted is that the portion of the population who identify as female are less likely to utilize the bikesharing service.  Prudent marketing would raise the additional question of "why" and find out ways that the bikesharing service is not working for them.  This would be an excellent opportunity for product updates based on the findings of that research.

## GRADING REQUIREMENTS MET -REMOVE ONCE GRADING IS COMPLETE
5 visualizations created in the challenge:
- Gender and User Use by Weekday -heatmap
- All Use per Hour -heatmap
- Gender Use per Hour -heatmap
- Duration of Checkout (Checkout Times for Users and Checkout Times by Gender) -line graphs

2 Visualizations (plus) from the module:
- Gender and User Use by Weekday (Gender Pie) -pie chart
- Starttime vs Stoptime (Starttime Hours -from "August Peak Hours") -horizontal bar graph
- End Destination for Bikes -geographical map

2 Additional visualizations for future use (instead of mentioning them in the summary, I have included them in my analysis):
- Starttime vs Stoptime (Stoptime Hours) -horizontal bar graph
- Filterable Usage by Day and Hour -vertical filterable bar graph
