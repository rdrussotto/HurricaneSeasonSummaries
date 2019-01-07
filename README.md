# HurricaneSeasonSummaries
Timeline plots of past hurricane seasons showing storm wind categories over time.

I wanted to make something like the hurricane season summary plots on Wikipedia (e.g. 
https://en.wikipedia.org/wiki/Timeline_of_the_2017_Atlantic_hurricane_season) but 
showing what category each storm was at any given time instead of just the maximum
category reached. 

As of 7 January 2019 I have made such plots for all Atlantic hurricane seasons from 
1851 through 2017. The 2018 season has not yet been added to the dataset; 
the 2017 season was added on 1 May 2018 so I expect 2018 to be added at a 
similar time this year. I have not yet made plots for Pacific hurricane seasons.

Hurricanes whose names were retired by the World Meteorological Organization
because they were particularly destructive are shown in bold. The maximum
category reached is shown on the right y-axis. 

In the root directory are iPython notebooks to split the data into 
individual files for the storms, with a different directory for each
season (these are in the "data" directory); to make the actual plots
and save as pdf and png files (stored in "plots");
and to define retired storm names.

Data is from the NOAA HURDAT2 archive available at 
https://www.nhc.noaa.gov/data/.  

I have used Python 3.6 with packages:  
numpy version 1.11.3  
matplotlib version 2.0.0  
pandas version 0.19.2  

You are welcome to make use of and adapt the plots and source code as long
as you acknowledge where they came from. I would also welcome any collaborators 
who want to expand this project.

Here are a few examples and a color legend: 
![Alt text](plots/1992.png?raw=true "1992")
![Alt text](plots/2005.png?raw=true "2005")
![Alt text](plots/2017.png?raw=true "2017")
![Alt text](plots/legend.png?raw=true "legend")
