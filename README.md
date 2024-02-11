
Analysis of TfL's Bike Hire System, Santander Cycles 

This project was done during my masters at King's College London in 2022.
The data used is from 1st January 2022 to 30th June 2022. It is obtained from the Transport for London (TfL) website for the Santander Bikes. The journey information is accessible under the ‘usage-stats/’ directory. The data is available in a .csv format for each week. The columns of this data are structured as rental ID, trip duration (in seconds), bike ID, end date, end station ID, start date, start station ID, and start station name. 

 
 Density maps displayed the variations in arrivals and departures throughout the day, as well as the paths taken by individual bike trips. 
A stochastic simulation using Poisson distribution was employed to estimate the negative customer experience to understand how the bike inventory level can affect the user experience. 
Python programming language and Microsoft Visual Studio Code was used for all the analysis and visualisation.

1. Docking stations- An interactive map showing the locations of the available docking stations for the Santander Cycles. This map displays all the docking points along with its information containing station ID, station capacity and station name in a cluster. Any station with a capacity of less than 15 is marked with a red circle, a capacity between 15 to 30 is marked with an orange circle, and the remaining stations with a capacity of over 30 are marked with a green circle.

2. Exploratory Data Analysis- An Exploratory Data Analysis (EDA) is conducted on the bike hire data. This included the study and visualisation of monthly, weekly, and daily rental counts along with the Origin-Destination (OD) matrix for all the docking stations in London. The most and least used stations were also analysed and compared.

3. Desnsity Maps- The density maps study the variation in the density of the arrival and departure rates. The departure and arrival count for each destination and origin, at a given hour are calculated, the difference of which is the net departure rate. The station having positive net departure i.e., net departure > 0, is plotted with a green-coloured circle, whereas the station having negative net departure i.e., net departure < 0, is plotted with a red-coloured circle. This density is calculated and plotted for 24 hours to highlight the usage of a station throughout the day in a video format. 
