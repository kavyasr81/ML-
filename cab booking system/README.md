### Cab boking system

Cab booking system is the process where renting a cab is automated through an app
throughout a city. Using this app, people can book a cab from one location to another location.
Being a cab booking app company, exploiting the understanding of cab supply and demand
could increase the efficiency of their service and enhance user experience by minimizing
waiting time.
Objective of this project is to combine historical usage pattern along with the open data sources
like weather data to forecast cab booking demand in a city.

#### Data description:

Dataset contains hourly renting data in the span of two years. Data is randomly divided into
train and test set. The total count of cabs booked in each hour covered by the
test set, using the information available prior to the booking period is predicted. The
train_label dataset is appended to train.csv as ‘Total_booking’ column.



Descriptions of the columns present in the dataset

- datetime-hourly date +timestamp 
- season-spring, summer, autumn, winter
- holiday-whether the day is considered a holiday
- workingday-whether the day is neither a weekend nor holiday
- weather-Clear , Cloudy,  Light Rain, Heavy 
- temp-temperature in Celsius
- atemp-"feels like" temperature in Celsius
- humidity-relative humidity
- windspeed-wind speed
- Total_booking-number of total booking (train_label contains the data)
