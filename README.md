# max_temp_ML
Machine Learning for Projecting Hot Day Frequency in a Changing Climate                                                                                                                                                     

The Problem Statement:                                                                                                                                                                

Climate Change has resulted in increased severity of hot days (hot day → A day where maximum temperature recorded is >35  degree Celsius).
Number of hot days per year is a commonly used heat hazard indicator. To predict number of hot days in a year is dependent on prediction of highest temperature recorded in a day.
So, the final problem statement is: To predict the maximum temperature at Pune by downscaling coarser data using Machine Learning approach (Downscaling → Bringing data from a coarser to finer scale).

Data Used:                                                                                                                                                                         
Study Site : Pune City, State of Maharashtra, India (18.5204°N, 73.8567°E)                                                                                                           
Input Features : Minimum, Maximum and Mean Temperature                                                                                                                              
(Downscaled CMIP5 GCM (IPSL-CM5A-LR) results based on the NEX-GDDP BCSD method, which is available at the nearest 0.25° by 0.25° grid box to Pune weather station location)           
Target Variable :  Maximum Temperature                                                                                                                                                     
(Observed daily maximum temperature (Tmax) over Pune is derived from the India Meteorological Department (IMD) 1° by 1° gridded daily station data)                                 
Period : 1976 to 2015                                                                                                                                                               

Methods used and compared:
Linear Regression                                                                                                                                                                  
Support Vector Regressor                                                                                                                                                            
Decision Tree Regressor                                                                                                                                                             
Multi Layer Perceptron Regressor                                                                                                                                                    
Random Forest Regressor                                                                                                                                                              
