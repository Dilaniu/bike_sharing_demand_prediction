# bike_sharing_demand_prediction
Build Machine learning based supervised model to predict hourly demand for bikes in Seoul 
# <b><u> Project Title : Seoul Bike Sharing Demand Prediction </u></b>

## <b> Problem Description </b>

### Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


## <b> Data Description </b>

### <b> The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.</b>


### <b>Attribute Information: </b>

* ### Date : year-month-day
* ### Rented Bike count - Count of bikes rented at each hour
* ### Hour - Hour of he day
* ### Temperature-Temperature in Celsius
* ### Humidity - %
* ### Windspeed - m/s
* ### Visibility - 10m
* ### Dew point temperature - Celsius
* ### Solar radiation - MJ/m2
* ### Rainfall - mm
* ### Snowfall - cm
* ### Seasons - Winter, Spring, Summer, Autumn
* ### Holiday - Holiday/No holiday
* ### Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

### conclusion
* Hour of the day holds most importance among all the features for prediction of dataset
* It is observed that highest number bike rentals counts in Autumn/fall Summer Seasons and the lowest in Spring season.
* We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day
* As we can see the top 5 important features of our dataset are: Season_winter, Temperature, Hour, Season_autumn, Humidity
* Peoples dont use rented bikes in no functioning day
* people tend to rent bikes when the temperature is between -5 to 25 degrees
* people tend to rent bikes when the visibility is between 300 to 1700
* for all the above experiments we can conclude that extreme gradient boosting and random forest regressor with hyperparameter tuning, we * * got the best results. (Lowest RMSE and highest R- square scores)
