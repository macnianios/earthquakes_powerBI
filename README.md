# earthquakes_powerBI
power bi report on eartquake events on Santorini

Files:

catalogue.csv : Data from https://www.gein.noa.gr/ypiresies-proionta/vasi-anazitisis/

earthquakes.pbit : Power Bi report template
 
DATA

The dataset includes the following:

• Origin Time (GMT)  

• Date (only date without time)

• Latitude  

• Longitude 

• Depth (km)  

• Location (how far from Thira (Santorini) did the event occurred)

• Magnitude (ML) (Size of the Event)

• Energy (Joyles)


Results

The statistical analysis concerns earthquakes of magnitude greater than 2 on the Richter scale that occurred within a 50 km radius of the islet of Anydros in the Cyclades between January 26 and February 19.

Using the two slicers, one can select the time period or the magnitude range they wish to examine.

The report includes:

•A map displaying the epicenters of the earthquakes.

•A table with statistical data, including the total number of earthquakes, average magnitude, maximum magnitude, minimum magnitude, and the equivalent magnitude if the total energy of all earthquakes had been released in a single event.

•A graph showing the evolution of the total number of earthquakes, the average magnitude, the maximum magnitude, and the minimum magnitude over the selected time period.

•A countplot recording the total number of earthquakes per magnitude.

•A countplot recording the total number of earthquakes per epicenter depth.

•A list of the five largest earthquakes by magnitude and their occurrence dates.


*An interesting observation is that over the last three weeks, more than 220 earthquakes above 4.0 on the Richter scale have occurred—a number that exceeds the total number of similar earthquakes in the entire country over the previous two years.

*Additionally, despite the decrease in the daily number of earthquakes and the average magnitude, there has been a streak of 19 consecutive days with at least one earthquake above 4.0 on the Richter scale.

Anyone interested can download their own earthquake dataset from www.gein.noa.gr/ypiresies-proionta/vasi-anazitisis, load it into the report, and obtain a corresponding analysis.

In the initial dataset, we added two hours to the recorded earthquake time to match the local time in Greece, calculated the energy of each earthquake, and extracted the date without the time component to facilitate the creation of graphs.
