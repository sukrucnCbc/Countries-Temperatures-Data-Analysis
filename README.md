# Climate Change Data Analysis

Some say climate change is the biggest threat of our age while others say it’s a myth based on dodgy science. We are turning some of the data over to you so you can form your own view.

## Dataset
### Climate Change: Earth Surface Temperature Data
### Exploring global temperatures since 1750
![data](https://climatedataguide.ucar.edu/sites/default/files/styles/node_lightbox_display/public/key_figures/climate_data_set/BEST_trend.png?itok=Bz1P6MhR)
![data](http://berkeleyearth.org/wp-content/uploads/2020/01/2019_Time_Series.png)
Even more than with other data sets that Kaggle has featured, there’s a huge amount of data cleaning and preparation that goes into putting together a long-time study of climate trends. Early data was collected by technicians using mercury thermometers, where any variation in the visit time impacted measurements. In the 1940s, the construction of airports caused many weather stations to be moved. In the 1980s, there was a move to electronic thermometers that are said to have a cooling bias.

Given this complexity, there are a range of organizations that collate climate trends data. The three most cited land and ocean temperature data sets are NOAA’s MLOST, NASA’s GISTEMP and the UK’s HadCrut.

We have repackaged the data from a newer compilation put together by the Berkeley Earth, which is affiliated with Lawrence Berkeley National Laboratory. The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 16 pre-existing archives. It is nicely packaged and allows for slicing into interesting subsets (for example by country). They publish the source data and the code for the transformations they applied. They also use methods that allow weather observations from shorter time series to be included, meaning fewer observations need to be thrown away.

In this dataset, we have include several files:

Global Land and Ocean-and-Land Temperatures (GlobalTemperatures.csv):

Date: starts in 1750 for average land temperature and 1850 for max and min land temperatures and global ocean and land temperatures
LandAverageTemperature: global average land temperature in celsius
LandAverageTemperatureUncertainty: the 95% confidence interval around the average
LandMaxTemperature: global average maximum land temperature in celsius
LandMaxTemperatureUncertainty: the 95% confidence interval around the maximum land temperature
LandMinTemperature: global average minimum land temperature in celsius
LandMinTemperatureUncertainty: the 95% confidence interval around the minimum land temperature
LandAndOceanAverageTemperature: global average land and ocean temperature in celsius
LandAndOceanAverageTemperatureUncertainty: the 95% confidence interval around the global average land and ocean temperature
Other files include:

Global Average Land Temperature by Country (GlobalLandTemperaturesByCountry.csv)
Global Average Land Temperature by State (GlobalLandTemperaturesByState.csv)
Global Land Temperatures By Major City (GlobalLandTemperaturesByMajorCity.csv)
Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to **deploy**(Bold Example) the project on a live system.

### Prerequisites

```
import numpy 
import pandas
import sklearn
import matplotlib
```

## Authors

* **Mert Çobanov** - *Initial work* 
* **Şükrücan Cebeci** -*in development*

## License

Berkeley Earth


