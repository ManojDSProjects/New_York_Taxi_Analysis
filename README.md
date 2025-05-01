# New_York_Taxi_Analysis

## Problem Definition  
Predicting the cost of a Taxi ride in New York given the time of the day, weather conditions and the region.
## Issues with Data  
### Negative Total cost  
![Negative Total cost](https://github.com/ManojDSProjects/New_York_Taxi_Analysis/blob/main/Images/Negative_Cost.jpg)  
I removed those values since they were comparatively less.  
## ML models Utilised  
1. Decision tree  
2. Random forest Regressor  
3. Gradient boost  
## Model Performance  
| Algorithm  |      MAE      |  RMSE | R2 |
|----------|:-------------:|------:|-------:|
| Decision tree |  8.729600 | 13.900400 | 0.305400 |
| Random forest |    7.607100   |   13.178900 | 0.375700 |
| Gradient boost | 8.624100 |    13.343300 | 0.360000 |  
## Data Source  
[Yellow Taxi Trip Records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
[About TCL](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
