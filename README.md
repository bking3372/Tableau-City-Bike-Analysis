# Tableau_City_Bike_Analysis

Background: The NYC Citi Bike Program has implemented an infrastructure for collecting data on the program's utilization.  Each month bike data is collected, organized, and made public on the Citi Bike Data webpage.


Objective:  Aggregate the data found in the Citi Bike Trip History Logs and develop two sets of visualizations based on the data.  Each set should encompass a dashboard with 2-5 visualizations per dashboard.  In addition, create a dynamic map of all bike stations that show's how a station's popularity changes over the given time period.  Finally, create a Tableau story that brings together the visualizations, map, and dashboards. 


Analysis:

Data:  The 2017 year was chosen for this analysis to get the most recent set of data that did not exceed the number of records that could be used in Tableau Public.  The data was organized and cleaned as follows:
- All twelve months were combined together
- Null values were eliminated (null values existed for birth year and user type); by eliminating these records, the data set fell below the 15,000,000 record threshold that can be used in Tableau Public
- Data was cleaned to 1) combine any duplicate station IDs/names that existed in the data; and 2) remove outlying variable which included ages over 100 years old and trips longer than 3 hours or less than 1 minute.
- Data prep was performed uisng Python and is located in the code folder. 


Key Findings:

1) Trip Occurrence / Duration
   -  During the week, trips occur most frequently during commute times (8-9 am and 5-6 pm); on weekends, trip occur most frequently in the afternoon hours.
   -  Most trips are between 5-9 minutes with average trip times slightly longer on the weekends.
   -  Shorter trip times during the week likely equate to more commuting trips or quick errands while users have more time to spend on weekend trips.
   -  One-time-use customers (non-subscribers) have higher proportions of weekend trips and slightly longer trip times than subscribers.
   -  One-time-use customers are more likely visitors to the city as opposed to subscribers which are likely city dwellers that are commuting and doing errands.
   
2) Differences During the Year (Month over Month)
   - There are more trips during the "nicer" months (Late Spring/Summer/Fall) as conditions are better suited to bike riding.
   - Trip times are also longer during these months; this is likely partially driven by more weekend trips which have longer average trip times.
   - There is greater use by one-time-customers during this time period as well; in fact, trips by these users are virtually non-existent January through March.
   
3) Map of City Bike Stations
   - The most popular bike stations for starting/ending trips is in Manhattan which is likely driven by the higher population in this area compared to outlying areas. 
   - Given the shorter trip times, it can also be inferred that people are staying within a small radius when taking trips and are not traveling to outer boroughs.
   
