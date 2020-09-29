# PV-forecasting-data

There are the meteorological data and power generation data of one PV power station used in Ultra-short-term Forecasting of Photovoltaic Power via RBF Neural Network. 

Meteorological data and power generation data of one PV power station in China from 2017 to 2018 are measured at 15-min intervals. 

Each column of the [raw_data.xls](https://github.com/AceBBang/PV-forecasting-data/blob/master/raw_data.xls) denotes different type of data as the following table.

| column | type of data |
|--|--|
| 1 | time |
| 2 | wind speed |
| 3 | wind direction |
| 4 | ambient temperature |
| 5 | pressure |
| 6 | humidity |
| 7 | solar irradience |
| 8 | PV power output |

The data at night and invalid data are excluded in the processed_data.xls. The invalid data include some days with no change in solar irradience, PV power output, or other types of data. After simple process, more than 20,000 sets of data are obtained.

Each column of the [processed_data.xls](https://github.com/AceBBang/PV-forecasting-data/blob/master/processed_data.xls) denotes different type of data as the following table.

| column | type of data |
|--|--|
| 1 | time(28 denotes 7:00, and 75 denotes 18:45, because night time data are excluded) |
| 2 | wind speed |
| 3 | wind direction |
| 4 | ambient temperature |
| 5 | pressure |
| 6 | humidity |
| 7 | solar irradience |
| 8 | PV power output |
