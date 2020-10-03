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
