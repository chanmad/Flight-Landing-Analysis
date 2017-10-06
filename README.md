# Flight-Landing-Analysis
Modeling FAA data for flight landing

Goal: To study what factors and how they would impact the landing distance of a commercial flight. 

Data: Landing data (landing distance and other parameters) from 950 commercial flights (not real data set but simulated from statistical models). See two Excel files ‘FAA-1.xls’ (800 flights) and ‘FAA-2.xls’ (150 flights).

Summary: 

The purpose of this study was to determine a safe landing distance. The data was obtained from FAA and contained about 850 unique values pertaining to flight landing. Few of the key variables involved were flight speeds in air and ground, height of the flight prior to landing and duration of the flight.  The data was first analyzed for outliers and then correlations were examined. Upon then weeding out the nonsignificant variables, the landing distance was regressed over the key variables and it was concluded that the speed in air and ground explain the landing distance. Also two models have been built and depending on the user preference, a more complex mix of models(based on whether the air speed is captured) or a simpler model based only on ground speed can be used to predict the landing distance.

