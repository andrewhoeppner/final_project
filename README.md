# Analysis of Sea Level Rise Over the next 1000 years.

## Overview:
The topic we chose to analyze is how the rise in sea levels have been affected by factors such as temperature change, CO2 emissions, and population across the globe dating back to 1992. The reason for selecting this topic is because it is relevant today, important for the future, and because we love our planet. Global warming is rising every year, and it's affecting the temperature and sea level across the world. With our research we want to predict if the sea level and temperature continues to rise every year, how our planet will look in the future.  We will be using linear regression algorithms in Machine Learning to be able to predict what levels the sea will rise to in the future. Linear regression is the most used algorithm in Machine Learning and a significant variable from the data set is chosen to predict the future values.

## Tools used to create this project
* Git and Github will be used to be able to work on this project as a team
* Excel will be used to examine data
* Python and jupyter note book will be use to write the code for the mechine learning model and to clean data.
* SQL will be used to store, retrieve, manage and manipulate data
* Tableau will be used to create data visualizations

https://public.tableau.com/app/profile/chace.daskalos/viz/RisingSeaLevelsVisuals/Story1?publish=yes
https://public.tableau.com/app/profile/andrew6464/viz/sealevel1993to2020/Story1?publish=yes
https://public.tableau.com/app/profile/andrew6464/viz/projectedsealevelthroughyear3000/Story1?publish=yes
* Google Slides will be used to present everything
https://docs.google.com/presentation/d/1C28iUiatFXmiYrv96hdG4Ypgk_fTbQ6fAfPpmc_o6hA/edit#slide=id.p                                   


## Machine Learning Model & Database Integration
Our machine learning model is located in sealevelprojection.ipynb and our datasets are loaded into the repository.

## Sources
* The CO2 data was collected from: https://www.statista.com/statistics/276629/global-co2-emissions/
* The surface temp data was collected from: https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land/ytd/12/1993-2018
* The ice data was collected from: https://www.epa.gov/climate-indicators/climate-change-indicators-ice-sheets
* The population data was collected from: https://www.worldometers.info/world-population/world-population-by-year/
* The sea level change data was collected from: https://www.epa.gov/climate-indicators/climate-change-indicators-sea-level#:~:text=When%20averaged%20over%20all%20of,as%20the%20long%2Dterm%20trend

## Results:
To examine our data, data was put togther and cleaned and examined with the following analysis.
![image](images/clean%20data.png)

We did the linear regression on adjusted sea level vs world population, global surface temperature anomaly, anartica ice mass change, greenland ice mass change, global c02 emission, and global seasurface temperature anomaly. We compared all these with adjusted sea level to see what is affecting the sea level rise.
![image](images/adjusted%20sea%20level%20vs%20antarctica%20ice%20mass%20change.png)

![image](images/adjusted%20sea%20level%20vs%20global%20co2%20emission.png)

![image](images/adjusted%20sea%20level%20vs%20global%20seasurface%20temperature%20anomaly.png)

![image](images/adjusted%20sea%20level%20vs%20global%20surface%20temperature%20anomaly.png)

![image](images/adjusted%20sea%20level%20vs%20greenland%20ice%20mass%20change.png)

![image](images/adjusted%20sea%20level%20vs%20world%20population.png)

We also used the correlation matrix to see the relationship between variables.

![image](images/correlation%20matrix.png)

## Conclusion:
Based on our analysis sea level is increasing every year, and by the next thousand years the sea level will be increase by 115.063 inches.

![image](images/future%20analysis%20part%201.png)
![image](images/future%20analysis%20part%202.png)
