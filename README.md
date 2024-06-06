# Olympic Games Dashboard

## Introduction

This dashboard was created to provide a comprehensive overview of the Olympic games throughout the years, with a focus on team performance and individual athlete achievements. The dashboard offers an in-depth analysis of the Olympics, and the feature of an interactive dashboard allows the user to easily navigate and explore the evolution of games. This dashboard also provides a few filters that allow users to delve into specific teams, athletes, sports, and editions of the Olympics. The dashboard is created with 4 pages: **About**, **Overview**, **Teams**, and **Athletes**, which we will explain further individually.


## Data Background
Historical data on the modern Olympic Games, from Athens 1896 to Rio 2016. Each row corresponds to an individual athlete competing in an individual event, including the athlete's name, sex, age, height, weight, country, and medal, and the event's name, sport, games, year, and city

| Field | Type | Description |
| --- | --- | --- |
| ID | Integer | Unique number for each athlete |
| Name | Character |Athlete's Name |
| Sex | Character | Athlete's Sex |
| Age | Numeric | Athlete's Age |
| Height | Numeric | Athlete's Height |
| Weight | Numeric | Athlete's Weight |
| Team | Character | Team's Name |
| NOC | Character | National Olympic Committee 3-letter code |
| Games | Character | Year and Season |
| Year | Integer | Game's Year |
| Season | Character | Game's Season |
| City | Character | Host City |
| Sport | Character | Sport | 
| Event | Character | Event |
| Medal | Character | Type of Medal Awarded |

Data Source: **Maven Analytics**

## Dashboard

### About
![Test-images-0](https://github.com/Geomatric15/Olympic-Dashboard/assets/167914482/ef38a606-e8f5-40c6-8315-b5667d3228f8)
The About page provides background information about the history of the Olympic Games and the data background description.

### Overview
![Test-images-1](https://github.com/Geomatric15/Olympic-Dashboard/assets/167914482/c72ac2e0-eb08-475b-a38a-db28005cda69)
The overview page provide the overall information of all olympic games all throughout the 120 years worth of data.
- **Number of Athletes**: Total number of all athletes who participated of all olympic games.
- **Number of Medal**: Total number of medal distributed to all athletes who won games.
- **Number of Teams**: Total number of teams participated in olympic games.
- **Sport Medal Performance**: Ranking of sports with most number of medal distributed.
- **Annual Number of Medals**: Number of medals distributed in yearly trend.
- **Medals Distribution**: Distribution of the medal distributed to athletes winners.
 

### Teams
![Test-images-2](https://github.com/Geomatric15/Olympic-Dashboard/assets/167914482/0992f6b4-93fe-4400-b408-5d897ea771c5)
The teams page provide the teams performance and achievements.
- **Team Selection**: Filter to provide information to selected team.
- **Medalist Percentage**: Percentage of athletes who won in total of team's atheletes.
- **Team Athletes**: total number of team's athletes.
- **Medaled Athletes**: Total Number of team's athletes won
- **Team Sports Performance**: Ranking of sports with most award the team's obtained.
- **Team Performance**: Team's performance throughout the olympics.
- **Medal Distribution**:  Distribution of the medal distributed to athletes winners.


### Athletes
![Test-images-3](https://github.com/Geomatric15/Olympic-Dashboard/assets/167914482/fb4abe85-0512-498d-857e-6c3ab0c7bdf8)
The Athletes Page provide individual athletes information, performance, and achievements.
- **Athlete Information**: Athlete personal information: age, height, weight, and BMI.
- **Athletes**: Filter to select specific individual to show information.
- **Olympic History**: Athlete's history: team, total number of sports they play, total games they participated, their recent play, and recent sport play in last olympic game.
- **Medals**: Athlete's Achievement: total number of medals won, medal distribution, sports and award.


