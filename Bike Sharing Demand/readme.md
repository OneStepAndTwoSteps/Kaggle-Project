# 数据说明

## Data Fields

datetime 
*   hourly date + timestamp  

season 
*   1 = spring, 
*   2 = summer, 
*   3 = fall, 
*   4 = winter 

holiday

*   whether the day is considered a holiday

workingday

*   whether the day is neither a weekend nor holiday

weather 
*   1: Clear, Few clouds, Partly cloudy, Partly cloudy
*   2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
*   3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
*   4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 

temp 
*   temperature in Celsius

atemp 
*   "feels like" temperature in Celsius

humidity 
*   relative humidity

windspeed 

*    wind speed

casual 
*   number of non-registered user rentals initiated

registered 
*   number of registered user rentals initiated

count 
*    number of total rentals

## clean data is important

__不同的清洗方式对模型的优劣有着很大的影响__

*   `Bike Sharing Demand.ipynb` 使用离散化数据来对模型进行训练（`score：0.49`）

*   `Bike Sharing Demand make new_feature.ipynb` 创建 `新的特征` 对模型进行训练（模型融合后：`score：0.36714`）

结论：我们一定要对数据做好足够的清洗，否则就会造成 `garbage in garbage out` 。


