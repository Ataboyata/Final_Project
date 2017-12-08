*Summary*
This stacked bar shows the total amount of flights by hour of departure in 2008 for the six biggest airlines in the US. Most of the flights start at 6 am in the morning, and the hourly departure stay in the range of 220k-240k for most of the day until 6pm. After this, the number of flights start decreasing through the night until it starts picking up again in the early morning.

Try clicking on any of the airlines in the Legend to see in detail how this trend applies for these six airlines.

Airlines:
WN: Southwest Airlines
AA: American Airlines
OO: SkyWest Airlines
US: US Airways
DL: Delta Airlines
MQ: Envoy Air (formerly American Eagle Airlines)

*Design*
The initial idea of the visualization was to show the percentage of delayed flights with stacked chart. But, in the end I decided that stacked bars with the total number of flights by airline would display something slighly more interesting. 

This type of bar plots were chosen because they display the biggest airlines by hour, with the one in the bottom with the biggest amount of flights per hour and the one in the top with the least amount of flights per hour.

The interactivity that was included allows the user to focus on any airline of their interest. 

*Feedback*
Feedback 1 - Sofia Torres Arpi
*The initial feedback I got form the 100% stacked bar chart, was that it seemed  that flights early in the morning were as important as flights later in the day. 
*Follow-up: As can be seen from the final visualization, this is not fair given than there are thousands of more flights later in the day.

Feedback 2 - Maru Torres Arpi
*The next feedback that I got was that it would be nice to see some interactivity in the graph. Trends are hard to see for the small airlines like DL.
*Follow-up: after adding interactivity it was easier to drill down to each airline and see if there were any trends during the day. 

Feedback 3 - Udacity Reviewer
*The visualization done was mainly exploratory, not explanatory.
*Follow-up: a title was addded and a small paragraph detailing the the main finding of the visualization was added. 


*Resources*
Data was obtained from:
Source: http://stat-computing.org/dataexpo/2009/the-data.html

Code for interactivity was taken from:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends 