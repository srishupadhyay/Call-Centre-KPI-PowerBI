# PWC Call Centre - KPI Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/0e1abd21-52c1-45a7-99ff-b326e4a75d9b" alt="Call Center" width="30%">
</p>


## Project Background</br>
This report analyzes the underutilized call center data from a PWC office to identify key performance trends and provide actionable insights to enhance operational efficiency and customer satisfaction.
The analysis focuses on two primary areas: **Overall Call center Performance & Individual Agent Performance**

### Objectives:
- Analyze key performance indicators (KPIs) to evaluate call center efficiency.
- Provide actionable recommendations to enhance call center performance and customer satisfaction.

Insights and recommendations are based on the following key areas and metrics:</br>
- Call Overview: An analysis of quarterly Customer Satisfaction Rating, Call Assessment Rate and the Call Type.
- Agent Performance: An assessment of Average Response Time (ART), Call Duration, Resolution Rate and Customer Satisfaction Rating.

## Data Structure
The database structure for this project includes a single table *call_centre_dataset*
 with a total row count of 5,000 for Q1</br>

<p align="center"><b><font size="10">ERD</font></b></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/012b6c8b-a2a3-4dbd-8de5-bd0f87fefd52" alt="ERD">
</p>
</br>


<p align="center">
  The dataset can be downloaded <a href="https://github.com/srishupadhyay/PWC-Digital-Accelerator-PowerBI/issues/2#issue-2526578190">HERE</a>
</p>


## Executive Summary</br>
### Overview Of Findings
The Customer Satisfaction Rating for the first quarter has declined from an average of 3.5 to 3.3, showing a peak of 4.11 in February especially during morning calls session. The Call Assessment percentage closed at 80.71% for the month of March showing a drop of 1.4% compared to that of January at 82.11% and the Resolution rate is below the normalcy level at 72.92%. Calls regarding streaming and Payment methods have the most number of query calls. The following sections will explore contributing factors and key areas of improvement.</br></br>


<p align="center">
  The interactive dashboard can be downloaded <a href="https://github.com/srishupadhyay/PWC-Digital-Accelerator-PowerBI/blob/c4d0d44612b08dc535fdc5d791e6f27a3149f910/PWC%20-%20Data%20%2B%20Dashboard%20File/Call%20Center%20Dashboard.pbix">HERE</a>
</p>


<h4 align="center">Call Overview Dashboard</h4>

<p align="center">
  <img src="https://github.com/srishupadhyay/Call-Centre-KPI-PowerBI/blob/ce5a7aeedb181dbe4bf99ac22507cec82f8c8e65/PICS/Call%20Over%20view%20Dashboard.png?raw=true" alt="Call Centre KPI Overview Dashboard">
</p>



<h4 align="center">Agent Performance Dashboard</h4>

<p align="center">
  <img src="https://github.com/srishupadhyay/Call-Centre-KPI-PowerBI/blob/ce5a7aeedb181dbe4bf99ac22507cec82f8c8e65/PICS/Agent%20Performance%20Dashboard.png?raw=true" alt="Agent Performance Dashboard">
</p>




## Call Trends

• **Customer Satisfaction Ratings:**</br>
  Jan - 3.45</br>
  Feb - 3.38</br>
  Mar - 3.37</br>
Customers are more satisfied with the Morning Calls which doing better at 3.47 compared to the Afternoon Calls at 3.38.</br>

• **Call Assessments:**</br>
  Q1 Overall - 81.08 %</br>
  Jan - 82.11 %</br>
  Feb - 80.32 %</br>
  Mar - 80.71 %</br>
The decline is primarily due to fewer calls being attended by agents. , causing the satisfaction rating to drop as well.</br>

## Agent Performance
<p align="center">
  <img src="https://github.com/user-attachments/assets/4efa419e-fdcc-45bd-8c0b-d7241a7c3c12" alt="aaa">
</p>

• **Average Response Time (ART):**</br>
ART for both Morning and Afternoon sessions for the entire quarter is 1.13 minutes. Joe and Martha take 1.18 and 1.16 minutes respectively to get back to the query calls. This does not affect Martha's customer satisfaction rating but Joe has the lowest satisfaction rating.</br>

• **Average Call Duration:**</br>
Average Call Duration for the quarter for all agents is 3.75 minutes.</br>
Long Call    - 5.98 minutes</br>
Medium Call  - 3.50 minutes</br>
Short Call   - 1.23 minutes</br>

• **Call Resolutions:**</br>
The overall Q1 resolution percentage stands at 72.92 which is still less than that of the required level of 80% meaning more than 15% of the complaints and queries regarding the services are not resolved. This is again a primary reason to why the satisfaction rates have been falled for Q1.</br>

Long Call    - 90.24%</br>
Medium Call  - 89.48%</br>
Short Call   - 90.50%</br>

Diane has the lowest score at 71.41 and the Dan having the highest at 74.41. No agent is crossing the required levels.

## Recommendations

![Animation - 1726448144214](https://github.com/user-attachments/assets/c2174613-c613-4fcc-8db2-7198996db2fc)

1. **Enhance Agent Training Programs**</br>
**No agent has call resolution percentage above 75%.** Even with the number of calls they are receiving, the agents are not able to convert them to resolved calls hence it is recommended that **Payment Issue Resolution and Subscription Management and Billing Workshops** are considered for the agents as Payments and Streaming have been the topmost hot topics. Participation of Diane and Martha is highly recommended.</br>

2. **Implement Intelligent Routing Systems**</br>
With the average wait time of 1.13 minutes , the agents are taking significantly long to return back to customers. An **intelligent routing system like ACD can be considered to direct calls to the most appropriate agents** based on their expertise, availability, and past performance. This can reduce response times and improve Customer Satisfaction Ratings, particularly for agents like Joe and Martha.






