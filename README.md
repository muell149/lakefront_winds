# lakefront_winds
Attempts to measure accuracy of global weather model forecasts (GFS, ECMWF) against actual measurements 


##Links

*[GFS git](https://github.com/ufs-community/ufs-weather-model/wiki)
*[GFS Document](https://www.weather.gov/media/mdl/marinetpb2.pdf)

##Steps

### Step 1 Locate Data

* ECMWF Forecast Model: [ECMWF Public Data Portal](https://apps.ecmwf.int/datasets/data/interim-full-daily/levtype=sfc/)

* GFS Forecast Model: [GFS Data](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-forcast-system-gfs)

* Observation: [NOAA Southern Mid-lake Buoy](https://www.ndbc.noaa.gov/station_page.php?station=45007)

### Step 2 Inital Scope

* Time Frame: July1-2 2019
* Mid Lake Buoy & closest grid-squares for each model
* Both models are run once/6hrs, 00,06,12,18Z
* GFS model forecasts in 1 hour time-steps, ECMWF forecasts in 3hr timesteps
* Measure accuracy of windspeed, wind direction
*ECMWF and GFSoutputs windspeeds and directions at 10m
 


