# Electric energy consumption trend identification

- [Situation](#Situation)
- [Consumption before monitoring](#Consumption-pattern-before-using-monitoring-app)
- [Consumption after monitoring](#Consumption-pattern-after-using-monitoring-app)
- [Bigger picture](#Overall-difference-before/after-using-monitoring-app)
- [Trend plot](#Relationship-between-saved-energy-and-temperature)
- [Correlation heatmap](#Correlation-insights)
- [Trends](#Trends)
- [Conclusions](#Conclusions)



# Situation
My client wants to see if it is worth monitoring electrical energy in order to optimze costs and consumption behaviour.
I was given a data sample for one month in order to extract insights and enable him to take the decision. 
 - Tasks
    - Opened data
    - Processed time series
    - Calculated before and after consumption
    - Extracted insights into Seaborn dashboards

# Consumption pattern before using monitoring app


![consumption patterns before app](https://user-images.githubusercontent.com/47668423/104204513-a5fcc600-542d-11eb-8fe1-000464bde389.png)

# Consumption pattern after using monitoring app


![after app dash](https://user-images.githubusercontent.com/47668423/104204504-a4330280-542d-11eb-8051-3230028b9557.png)

# Overall difference before/after using monitoring app


![diff before after](https://user-images.githubusercontent.com/47668423/104204515-a6955c80-542d-11eb-96fa-d3dae417f4cc.png)

![saved KwH violin](https://user-images.githubusercontent.com/47668423/104348195-b41c1680-5501-11eb-9a12-ba21097c64b4.png)

# Relationship between saved energy and temperature

![newplot (8)](https://user-images.githubusercontent.com/47668423/104348188-b2525300-5501-11eb-81ca-16beee117a18.png)


# Correlation insights


![Trend corr](https://user-images.githubusercontent.com/47668423/104204516-a6955c80-542d-11eb-9de6-f0c4ebfc7362.png)


# Trends 
  - The more hours the more active the larger consumption.
  - At the begining of the week and end of the week.
  - There are more active hours and therefore consumption.
  - The worst the weather the higher kwH consumption.

# Conclusions 
Not big differences spotted between situation with app and before app, most propbably because consumption behaviour was much the same and data was only processed for 1 month.
Nevertheless differences show clear benefits of using monitoring app in order to optimize costs and consumption behaviour.
The short answer is Yes use the monitoring app as on a longer term it may be even more usefull. 
