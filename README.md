# UK_Election
This project visualizes the results of the 2015 United Kingdom General Election using different cartographic approaches to represent political data. The visualizations highlight geographic voting patterns, party dominance across constituencies, and share of votes.

## Maps Produced
1. Choropleth Map of Share of Vote
   
![2015_UK_Election_Shareofvote](https://github.com/user-attachments/assets/66430cd7-67fb-4750-94f2-9fad352744bf)

Description:
This map uses a choropleth style to represent the percentage share of vote per constituency for the winning party. The data is binned into four categories:

25% – 39% (lightest green)
40% – 53%
54% – 67%
68% – 81% (darkest green)

Purpose:
Highlights how dominant the winning party was in each constituency. Darker greens reflect stronger electoral majorities, while lighter greens show more marginal wins.


2. Multivariate Dot Density Map of First Votes

![2015_UK_Election_Constituencies](https://github.com/user-attachments/assets/2562dc34-dbf6-49f6-a935-bbaaf4b36d3a)

Description:
This dot density map shows first-past-the-post votes with each dot representing approximately 2,000 votes. Votes are colored by party:

🟦 Conservative (Blue)

🔴 Labour (Red)

🟨 Liberal Democrats (Yellow)

🟩 Scottish National Party (Green)

⚫ Scottish National Library (Black)

🟣 Other parties (Purple)

Purpose:
Illustrates spatial distribution of voter support across the UK by party. It conveys not just which party won but the volume and location of each party's support base.

3. Constituency Map by Winning Party

![2015_UK_Election](https://github.com/user-attachments/assets/6f0b352a-e9c8-4eb9-bd08-eb233d61747c)

Description:
This map shows each parliamentary constituency colored by the party that won the seat in the 2015 election:

🟦 Conservative

🔴 Labour

🟨 Liberal Democrats

🟩 Green

🟪 UK Independence Party

⚫ Sinn Féin

🟫 Scottish National Party

🟧 Others

Purpose:
Provides a clear picture of party dominance and regional voting patterns by identifying the first-place party in each constituency.

## Tools and Technologies
GIS Software: Likely QGIS, ArcGIS, or Python-based tools (e.g., GeoPandas, Matplotlib, Seaborn, or Basemap)

Data Sources:

2015 UK General Election voting data by constituency

UK Parliamentary Constituency shapefiles (e.g., from the UK Data Service or Ordnance Survey)

Base maps from OpenStreetMap / Esri

