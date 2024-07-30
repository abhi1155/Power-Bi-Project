# Call Center Analysis Dashboard



# Problem Statement



In today's dynamic business environment, efficient call centre operations are crucial for maintaining high customer satisfaction levels. This project focuses on leveraging Power BI to analyze key metrics that drive call centre performance and customer experience.

Through insightful visualizations and data-driven analysis, this project aims to provide actionable insights for enhancing operational effectiveness and delivering superior customer service in the call centre environment.


# Objectives

1) Call Volume: Understanding the volume of incoming calls over time.
2) Issue Categories: Categorizing and prioritizing topics that require resolution.
3) Call Handling: Analyzing the efficiency of calls answered and resolved.
4) Customer Satisfaction: Measuring overall satisfaction ratings derived from customer feedback.
5) Response Time: Evaluating the average speed of answer for calls, a critical metric for service quality.
6) Agent Performance: Utilizing a performance quadrant to assess agents based on average handle time and calls answered, aiming to optimize operational efficiency.

# Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : click on Table to review sheet to analyze it for Preprocessing & Cleaning. 
- Step 3 : It was observed that in none of the columns errors & empty values were present .
- Step 4 : from the visualization pane we used slicer to select Agent & Topic for which we required data.
- Step 5 : We also used slicer tool & Date column from data sheet. we can select duration using date for which we require specific data.
- Step 6 : We have used Donut chart which shows Data about Total Calls Answered (Yes/No) and Calls or Query Resolved for specific Topic (Yes/No).
- Step 7 : We have used Matrix from built visual to show Data for specific agent. like calls they Answered , Calls they Resolved, Avg. Satisfaction rating & Average speed of Answer
           for Matrix we created two new measures Answeres(Y) & Resolved(Y)
- Step 8 : We used Gauge built visual in visualization pane which shows Average Satisfaction Rating. Here we used satisfaction rating column in data sheet 
- Step 9 : We Created Scatter Chart to show Average satisfaction rating for particular Agent.
- Step 10 : Secondly we have used Line chart to show Daily Analysis for calls Answered, Calls Resolved and Total Calls received on that particular Day
- Step 11 : We Have used Cards from visualization pane to show count for Total Calls, No of Agent, No of Topics, Calls Answered & Calls Resolved.
            we have selected different column from xl sheet for different cards to show counts for different condition.
           

 # Report Snapshot (Power BI DESKTOP)

 Page 1
<img width="611" alt="Screenshot 2024-07-17 203246" src="https://github.com/user-attachments/assets/018fff26-5f43-47b4-a790-a9c569fd5489">

Page 2
<img width="605" alt="Screenshot 2024-07-17 203317" src="https://github.com/user-attachments/assets/f3c8daef-925e-45cb-a377-4e1a814948e3">

# Conclusion & Insights
1) Total calls Received is 5000, Calls Answered is 4054, Calls Resolved is 3646.
2) Average Speed of Answer after considering All Agents & Topic is 67.52.
3) Maximum Calls arrived in the month of January.
4) Total Calls that are Not answered & Answered is 946 & 4054 Respectively.
5) Total Calls That are Not Resolved & Resolved is 1354 & 3646 Respectively.
6) Agent Martha Has Maximun average satisfaction rating.
7) Agent Jim answered maximun calls & also resolved maximum Calls.





        
