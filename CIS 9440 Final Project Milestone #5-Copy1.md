# NYC Subway Protective Platform Doors 
- Author(s): Ying Chen, Jiawen Chen,Gexing Ding, Wanmei He
- Date Created: 5/6/2022
- Class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:

More and more incidents in recent years where riders were shoved onto the tracks. For passengers’ safety, there is a need to add platform screen doors or protective facilities at subway station.

Description of the issues or opportunities the project will address:

Metropolitan Transportation Authority (MTA) provides convenient transportation in New York City, but how many subway accidents have occurred in 2021, 2020, or 2019 ? How many injuries case are there ? Is the number of accidents increasing or decreasing ? Which stations will need to install the platform screen door the most ?
To answer these questions, our data warehouse will combine the number of subway stations, daily ridership data, subway stations events data to analyze the situation of each station.

Project Business or Organization Value:

Since more and more incidents and injuries in the subway during recent years, people are more preferred on Uber or other alternatives. If there is a clear analysis of the safety level of each subway station. MTA department can provide a budget plan to install platform screen door or optimize protective facilities at different stations. They can also offer the transparency plan for all riders, which can increase rider’s trust
and thus increase its daily ridership. Also, this plan may be increase revenue by reducing compensation for injuries and other maintenance costs.

Data Sources:

1. MTA NYC Incidents https://data.ny.gov/Transportation/511-NY-MTA-Events-Beginning-2010/i8wu-pqzv
2. Subway Station Data https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49
3. Subway Ridership Data https://new.mta.info/agency/new-york-city-transit/subway-bus-ridership-2020

### Business Requirements Definition

List of Data Warehouse KPI's:

1. Average annual ridership per station
2. Average daily ridership per station based on weekdays and weekends.
3. Total number of subway stations by borough
4. Total accidents/injuries case by category by borough in 2020
5. The number of subway lines per station


### Dimensional Model

![Dimensional Model](https://user-images.githubusercontent.com/70614026/167228651-d58e396c-b6dd-4fab-8412-7ae45f3b1b11.png)

This project's Kimball Bus Matrix:

<img width="587" alt="Kimball BUS Matrix" src="https://user-images.githubusercontent.com/70614026/167535770-c7ad38dd-3c9f-4fd7-b10d-973641c175f4.PNG">




### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Tree Map for Average Annual Ridership per Station
<img width="473" alt="1  Annual Ridership" src="https://user-images.githubusercontent.com/70614026/167955064-f2093a22-ae93-4f24-bc93-e201d49e324a.png">


2. Tree Map - Compariosn of Average Daily Ridership per Station based on Weekdays vs Weekends
<img width="592" alt="2  Average Weekdays" src="https://user-images.githubusercontent.com/70614026/167954968-7fe68100-61c5-4826-b4fe-a04a9d4a5137.png">
<img width="569" alt="2   Average Weekends" src="https://user-images.githubusercontent.com/70614026/167955028-70c3b17c-f369-491c-b4cb-4e69690b9deb.png">


3. Packed Bubble chart for Total Number of Subway Stations by Borough
<img width="347" alt="3  Subway Station by Borough" src="https://user-images.githubusercontent.com/70614026/167275241-8a4f19a1-2978-42a0-b766-e538000e4ab4.png">

4. Stacked bar chart for Total Accidents/Injuries Case by Category by Borough in 2020
<img width="548" alt="4  Incidents cases by Borough and Category in 2020" src="https://user-images.githubusercontent.com/70614026/167313295-01af468e-a407-4f0b-acc8-90c3a0fd28d3.png">

5. Tree Map for The Number of Subway Lines per Station
<img width="476" alt="5  Subway Line per Station" src="https://user-images.githubusercontent.com/70614026/167954864-129a35a5-989e-4cf8-9de6-afee3cdcd806.png">



BI Application Wireframe design:
![WireFrame](https://user-images.githubusercontent.com/70614026/167229669-6f0d17d9-27df-44b7-863e-4d5959b9ea4e.jpg)


Picture of final Dashboard:


## Use correct file path here to show picture of Dashboard:

Dashboard #1 
![Dashboard 1 ](https://user-images.githubusercontent.com/70614026/167967282-dbbc76e3-4d52-4863-95a8-efc3f959c4a7.png)


Dashboard #2
![Dashboard 2](https://user-images.githubusercontent.com/70614026/167967328-3d3c55ca-9c17-4ea5-817e-006a54f529e6.png)



### Deployment

The project was deployed on Tableau Public: (link here)

Dashboard 1: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard2/Dashboard1?publish=yes

Dashboard 2: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard2/Dashboard2?publish=yes


```python

```
