# PV-forecasting-data

There are the meteorological data and power generation data of one PV power station used in Ultra-short-term Forecasting of Photovoltaic Power via RBF Neural Network. 

Meteorological data and power generation data of one PV power station in China from 2017 to 2018 are measured at 15-min intervals. 

Each column of the raw_data.xls denotes different type of data as the following table.

| column | type of data |
|--|--|
| 1 | time |
| 2 | solar irradience(invalid) |
| 3 | wind speed |
| 4 | wind direction |
| 5 | ambient temperature |
| 6 | pressure |
| 7 | humidity |
| 8 | solar irradience |
| 9 | PV power output |

The data at night and invalid data are excluded in the processed_data.xls. After simple process, more than 20,000 sets of data are obtained.

Each column of the processed_data.xls denotes different type of data as the following table.

| column | type of data |
|--|--|
| 1 | time(28 denotes 7:00, and 75 denotes 18:45, because night time data are excluded) |
| 3 | wind speed |
| 4 | wind direction |
| 5 | ambient temperature |
| 6 | pressure |
| 7 | humidity |
| 8 | solar irradience |
| 9 | PV power output |
