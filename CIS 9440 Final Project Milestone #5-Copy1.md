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

<img width="589" alt="Kimball BUS Matrix" src="https://user-images.githubusercontent.com/70614026/167228719-29e4519b-a1fd-4102-9f65-80bac2e780fb.PNG">




### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for Average Annual Ridership per Station
<img width="542" alt="1  Annual Ridership Top 25" src="https://user-images.githubusercontent.com/70614026/167271245-b0e73696-3665-4e02-9110-de0d87268d24.png">


2. Bar Chart - Compariosn of Average Daily Ridership per Station based on Weekdays vs Weekends
<img width="545" alt="2  Average Weekdays Top 25" src="https://user-images.githubusercontent.com/70614026/167271260-053180b7-80e4-440c-ae49-8e3c5f1c7544.png">
<img width="545" alt="2   Average Weekends Top 25" src="https://user-images.githubusercontent.com/70614026/167271274-5908c7ab-f263-47ac-9550-b71ce63ef33b.png">


3. Packed Bubble chart for Total Number of Subway Stations by Borough
<img width="344" alt="4  Subway Station by Borough" src="https://user-images.githubusercontent.com/70614026/167271302-cda37da8-f91e-4f71-b8cf-8757b56fccd4.png">

4. Stacked bar chart for Total Accidents/Injuries Case by Category by Borough in 2020

<img width="249" alt="3  Incidents cases by Borough and Category in 2020" src="https://user-images.githubusercontent.com/70614026/167271287-33a398ba-de83-4833-b34a-2d676bb1eb11.png">

5. Bar Chart for The Number of Subway Lines per Station
<img width="631" alt="5  Subway Line per Station" src="https://user-images.githubusercontent.com/70614026/167271334-a9d2e581-b4b0-4a0d-b6ae-ef12118d9302.png">


BI Application Wireframe design:
![WireFrame](https://user-images.githubusercontent.com/70614026/167229669-6f0d17d9-27df-44b7-863e-4d5959b9ea4e.jpg)


Picture of final Dashboard:


## Use correct file path here to show picture of Dashboard:

Dashboard #1 
![Dashboard 1 ](https://user-images.githubusercontent.com/70614026/167271365-0f7e2139-1913-47ee-84f4-e0cc691fa901.png)


Dashboard #2
![Dashboard 2](https://user-images.githubusercontent.com/70614026/167271378-014ec20e-e51e-4c85-9aa2-bbce778e97d3.png)



### Deployment

The project was deployed on Tableau Public: (link here)

Dashboard 1: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard2/Dashboard1?publish=yes

Dashboard 2: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard2/Dashboard2?publish=yes


```python

```
