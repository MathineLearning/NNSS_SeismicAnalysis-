# NNSS_SeismicAnalysis
***DISCLAIMER: This was a student lead project attempting to solve a research problem provided by the Nevada National Security Site (NNSS). This does not provide a full proof analysis and should only be used to demonstrate the coding ability of the team. 

# Objective
Provide a method of differentiating natural seismic events from non-natural seismic events. Natural seismic events would be any kind of earthquake. A non-natural seismic event could be anything from animals walking near the sensor, mining demolitions to nuclear weapons tests. The end game would be to identify if weapons testing is occuring around the world and if possible to identify the location of these tests. However, this project attempts to just identify if the events are natural or non-natural. The main toolbox used was Obspy

# What is Included
1. A visual algorithm isolating the events of one day and analyzing each anomaly for P and S waves. P waves, primary waves, that arrive first and S waves, secondary waves, arrive second

2. An algorithm that takes each anomaly and writes it to an excel spreadsheet

3. A script that takes each spreadsheet and combines the anomalies into one spreadsheet

4. Neural Network code


# Isolating Events VisualizationAlgorithm
This script allows you to view the plots of the whole day and any anomalies that the  algorithm detects. This was developed using Anaconda and Spyder, therefore using this in other editors could produce different results as the graphs appear in the Spyder command window. This algorithm works by:
- Searching to see if any amplitude values are above 200 and collects these points in a list
- Starting from the first point it checks if the next point is greater than 4000 centiseconds in time (using this terminology because it is "written" this way in the code) 
- 
