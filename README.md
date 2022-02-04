# bikesharing

## Project Overview
The purpose of the project was to use data from New York City's Citi Bike program and see if it would be possible to recreate the program in De Moines, Iowa. In order to complete this analysis, we have used Python's pandas library to clean up the data and then created visualizations of that data using Tableau. Tableau provides the tool to create powerful analytic dashboards and tell a clear story that can be easily shared with others. Tableau can be simple, requiring little-to-no-coding, or quite complex, requiring some experience to write custom code in so-called calculated field. For this project I am using:


- Tableau to create visualizations, dashboard and story.
- Pandas to convert integers to a datetime datatype.


## Resources
 - **Data Source**: 
   - [Citi Bike Data](https://ride.citibikenyc.com/system-data)
   - [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/index.html/201908-citibike-tripdata.csv.zip)

 - **Software:**

   - VS Code, Anaconda Navigator, Jupyter Notebook, Tableau Public 2020.3.2
 
 - **Languages & Environment:**
   - Pandas, Python 3.7

## Results
**Deployed Tableau Analysis**
[link to dashboard](https://public.tableau.com/app/profile/nensi7308/viz/NYC_Citibike_Challenge_16436476259450/NYCCityBikeStory)

**New York Citi Bike data visualizations for August 2019**

<img width="673" alt="Screen Shot 2022-02-04 at 3 29 43 PM" src="https://user-images.githubusercontent.com/92277581/152605671-f26b6538-dc60-4290-b7f5-8639f4e98f28.png">


To compelete this analysis, we have 4 things to check:
1. How long do users bike for?
2. Who is using the bikes?
3. Start and end location for biking?
4. When are users using the bikes?



**How long do users bike for?**
This visualization shows the length of time of every bike ride during the month of August in 2019. 

<img width="518" alt="Screen Shot 2022-02-02 at 5 49 39 PM" src="https://user-images.githubusercontent.com/92277581/152257073-1096b70f-c3c9-4aa7-94d6-10d5f3516a84.png">

- One way to see this side of the story is that users checkout bike for a single trip and return bike to the station (3 hour) or may rent the bike and keep it until their return trip (8+ hours).

**Who is using the bikes?**

This visualization shows the breakdown of riders by gender and duration of times showing that most of the users are men.


<img width="503" alt="Screen Shot 2022-02-02 at 5 51 39 PM" src="https://user-images.githubusercontent.com/92277581/152257248-f0770c3e-812b-43af-be96-82da7e5de44b.png">

To further these findings, this visualizations shows that the most common user is a male subscriber (meaning that they have signed up for a long term contract with citi bike) and their most frequent day of the week to ride on is Thursday.


<img width="514" alt="Screen Shot 2022-02-02 at 5 52 50 PM" src="https://user-images.githubusercontent.com/92277581/152257353-46a5100f-8c09-4b7b-b7f5-f0774b45e67e.png">

- Male users take approximately 3 times more rides than the female users.


**Start and End locations for bikeRide?**
These two visualizations show the top starting and ending locations. The first thing to note is that most rides start in the most populous areas in mid and lower Manhattan. Second, due to shorter ride times, the ending locations are also in those same popular areas. From those two graphs we can see the most popular starting and ending locations. Orange color represent subscribers, while blue represent customers. Larger bubbles represent locations with the highest number of trips, and smaller bubbles represent lowest number of trips. From the graph we can see which stations are more popular amongst subscribers vs. customers and what areas are more popular than others. Downtown area is much more popular than surrounding areas, yet it is as important for surrounding areas to have bike services, in order to ensure good customer experience.

<img width="775" alt="Screen Shot 2022-02-03 at 10 50 57 AM" src="https://user-images.githubusercontent.com/92277581/152605526-99df96fc-5cfb-4c7b-bf6f-5ceae388815b.png">
<img width="706" alt="Screen Shot 2022-02-03 at 10 50 27 AM" src="https://user-images.githubusercontent.com/92277581/152605539-293cc376-5044-45bc-8d9d-901424af6b47.png">




**When are users using the bikes?**
This visualizations shows that weekday rider traffic peaks at traditional commuting times, while weekends see gradual use throughout the day.

<img width="371" alt="Screen Shot 2022-02-02 at 5 58 36 PM" src="https://user-images.githubusercontent.com/92277581/152257879-de92d228-a382-409f-80be-17c73d2994a6.png">

To further these findings, this visualization shows a similar patterns when broken down between genders.

<img width="663" alt="Screen Shot 2022-02-02 at 5 59 58 PM" src="https://user-images.githubusercontent.com/92277581/152258029-c08382e0-cded-471d-be07-0cca706f295c.png">

- Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
- Weekend rides are highest from 10:00 AM to 7:00 PM.
- Those rides are mostly taken by male users.

## Summary
Based on the findings above, these are the top takeaways to create a successful citi bike program in De Moines. The data shows high activity of the bike sharing service in New York during the month of August 2019.
The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.
Additional analysis would be beneficial by :

- Comparing data for different months to determine trends across the year,
- Including weather data to find the correlation between the weather and the rides.





