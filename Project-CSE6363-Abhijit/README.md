Files were made in JupyterLab. They can be run in any environment that supports .ipynb files.

The .csv files are in the zip. Input file locations into the pd.read_csv('location/US_Accidents_June') line of code respectively for data

Data Description:

ext_format
ID
This is a unique identifier of the accident record.

text_format
Source
Indicates source of the accident report (i.e. the API which reported the accident.).

grid_3x3
TMC
A traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.

grid_3x3
Severity
Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay). Note that severity reported by different sources may differ in their underlying impact on traffic, so please separate data from different sources when doing severity-based analysis. 

calendar_today
Start_Time
Shows start time of the accident in local time zone.

calendar_today
End_Time
Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.

grid_3x3
Start_Lat
Shows latitude in GPS coordinate of the start point.

grid_3x3
Start_Lng
Shows longitude in GPS coordinate of the start point.

vpn_key
End_Lat
Shows latitude in GPS coordinate of the end point.

vpn_key
End_Lng
Shows longitude in GPS coordinate of the end point.

grid_3x3
Distance(mi)
The length of the road extent affected by the accident.

text_format
Description
Shows natural language description of the accident.

grid_3x3
Number
Shows the street number in address record.

text_format
Street
Shows the street name in address record.

text_format
Side
Shows the relative side of the street (Right/Left) in address record.

text_format
City
Shows the city in address record.

text_format
County
Shows the county in address record.

text_format
State
Shows the state in address record.

text_format
Zipcode
Shows the zipcode in address record.

flag
Country
Shows the country in address record.

text_format
Timezone
Shows timezone based on the location of the accident (eastern, central, etc.).

text_format
Airport_Code
Denotes an airport-based weather station which is the closest one to location of the accident.

calendar_today
Weather_Timestamp
Shows the time-stamp of weather observation record (in local time).

grid_3x3
Temperature(F)
Shows the temperature (in Fahrenheit).

grid_3x3
Wind_Chill(F)
Shows the wind chill (in Fahrenheit).

grid_3x3
Humidity(%)
Shows the humidity (in percentage).

grid_3x3
Pressure(in)
Shows the air pressure (in inches).

grid_3x3
Visibility(mi)
Shows visibility (in miles).

text_format
Wind_Direction
Shows wind direction.

grid_3x3
Wind_Speed(mph)
Shows wind speed (in miles per hour).

grid_3x3
Precipitation(in)
Shows precipitation amount in inches, if there is any.

text_format
Weather_Condition
Shows the weather condition (rain, snow, thunderstorm, fog, etc.)

check
Amenity
A POI annotation which indicates presence of amenity in a nearby location.

check
Bump
A POI annotation which indicates presence of speed bump or hump in a nearby location.

check
Crossing
A POI annotation which indicates presence of crossing in a nearby location.

check
Give_Way
A POI annotation which indicates presence of give_way in a nearby location.

check
Junction
A POI annotation which indicates presence of junction in a nearby location.

check
No_Exit
A POI annotation which indicates presence of no_exit in a nearby location.

check
Railway
A POI annotation which indicates presence of railway in a nearby location.

check
Roundabout
A POI annotation which indicates presence of roundabout in a nearby location.

check
Station
A POI annotation which indicates presence of station in a nearby location.

check
Stop
A POI annotation which indicates presence of stop in a nearby location.

check
Traffic_Calming
A POI annotation which indicates presence of traffic_calming in a nearby location.

check
Traffic_Signal
A POI annotation which indicates presence of traffic_signal in a nearby location.

check
Turning_Loop
A POI annotation which indicates presence of turning_loop in a nearby location.

text_format
Sunrise_Sunset
Shows the period of day (i.e. day or night) based on sunrise/sunset.

text_format
Civil_Twilight
Shows the period of day (i.e. day or night) based on civil twilight.

text_format
Nautical_Twilight
Shows the period of day (i.e. day or night) based on nautical twilight.

text_format
Astronomical_Twilight
Shows the period of day (i.e. day or night) based on astronomical twilight.