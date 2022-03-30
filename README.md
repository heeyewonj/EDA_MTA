## Exploratory Data Analysis: MTA Mask Force Placement



### Abstract 

Big Apple Cares tries to place Mask Force volunteers at the NYC subway stations and distribute free masks for riders who are not wearing a mask. The goal of this project was to explore and analyze MTA ridership using MTA turnstiles data. Exploratory Data Analysis (EDA) was performed to satisfy the client's solicit and answer how to place Mask Force Volunteers at stations to maximize the mask distribution. I answered the following questions: (1) which boroughs are busier than others (2) which stations have more traffic than others? (3) what day/time volunteers should be placed? I found the top 10 busiest stations in Manhattan. Subway stations are busier on weekdays than weekends and holidays. Different stations have more traffic than others depending on time (daytime versus evening).

### Design

Masks are still required on public transit and at stations for COVID safety. Wearing masks is proven to keep transit riders and frontline employees safe from virus transmission. For public safety, Big Apple Cares, a New York City nonprofit organization, with MTA has recently created a new volunteer program to distributes free masks to transit customers. Big Apple Cares has requested the most efficient ways to place Mask Force volunteers so that Mask Force can give out free masks for those who are not wearing a mask at subway stations. I performed Exploratory Data Analysis (EDA) to answer how to maximize free mask distribution for those without wearing masks.

### Data

The datasets used in the project were: MTA turnstiles data (from March 27, 2021, to August 13), 2021, MTA station location data, and NYC borough maps data. MTA turnstiles data includes station names, the number of passenger entries, time, and dates. MTA station location data includes (need to complete here!). NYC borough maps data

### Algorithms

I cleaned the MTA turnstiles data. The dataset contained inconsistent and duplicating data. Next, the values for the turnstiles counter (i.e., the number of passenger entries) are also cumulative. I calculated the number of daily entries by aggregating time and dates.

For the data analysis, ridership trends were observed by different levels (i.e., level of NYC boroughs, stations, and day/time). This observation helps to explore which borough and station have the highest traffic and when the volunteers should be placed during the week. 

### Tools

1. Data manipulation: Numpy, Pandas
2. Visualization: Matplotlib, Seaborn, Geopandas
3. Data processing: SQLalchemy


### Communication
For code, please find "code" in the repo and "slide.pdf" file for the Powerpoint slides.
