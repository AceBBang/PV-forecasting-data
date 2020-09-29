# PV-forecasting-data

There are the meteorological data and power generation data of one PV power station used in Ultra-short-term Forecasting of Photovoltaic Power via RBF Neural Network. 

Meteorological data and power generation data are measured at 15-min intervals. 

To simplify the experiment, the data at night and invalid data are excluded. 
Finally, more than 20,000 sets of data are obtained.

Each column of the xls file denotes different type of data as the following table.

| column | type of data |
|--|--|
| 1 | time(28 denotes 7:00, 75 denotes 18:45) |
| 2 | predicted solar irradience(invalid) |
| 3 | wind speed |
| 4 | wind direction |
| 5 | ambient temperature |
| 6 | pressure |
| 7 | humidity |
| 8 | solar irradience |
| 9 | current PV power output |
| 10 | PV power output before 15 mins |
| 11 | PV power output before 30 mins |
| 12 | PV power output before 45 mins |
| 13 | PV power output before 60 mins |
| 14 | PV power output before 75 mins |
| 15 | PV power output before 80 mins |
| 16 | PV power output before 95 mins |
| 17 | PV power output before 120 mins |
| 18 | PV power output before 135 mins |
| 19 | PV power output before 150 mins |
| 20 | PV power output after 15 mins (the output to be predicted) |
