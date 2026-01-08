# Metadata

## London Fire Brigade data

- [Source](https://data.london.gov.uk/dataset/london-fire-brigade-incident-records-em8xy)
- Datasets include individual incident records and mobilisation data from 2009 onwards.
- Columns

| Column                                 | Sample record          | Description                                                             | Extra Notes            |
| -------------------------------------- | ---------------------- | ----------------------------------------------------------------------- | ---------------------- |
| IncidentNumber                         | 000008-01012018        | LFB Incident Number                                                     |                        |
| DateOfCall                             | 01-Jan-18              | Date of 999 call                                                        |                        |
| CalYear                                | 2018                   | Year of 999 call                                                        |                        |
| TimeOfCall                             | 00:04:25               | Time of 999 call                                                        |                        |
| HourOfCall                             | 0                      | Hour of 999 call                                                        |                        |
| IncidentGroup                          | False Alarm            | High level incident category                                            |                        |
| StopCodeDescription                    | AFA                    | Detailed incident category                                              |                        |
| SpecialServiceType                     |                        | Further detail for special services incident categories                 |                        |
| PropertyCategory                       | Non Residential        | High level property descriptor                                          |                        |
| PropertyType                           | Mosque                 | Detailed property descriptor                                            |                        |
| AddressQualifier                       | Within same building   | Qualifies location of actual incident relevant to category above        |                        |
| Postcode_full                          | N2 8AY                 | Postcode                                                                | redacted for Dwellings |
| Postcode_district                      | N2                     | Postcode Districs                                                       |                        |
| UPRN                                   | 200220110              | Unique Property Reference Number                                        | redacted for Dwellings |
| USRN                                   | 20013420               | Unique Street Reference Number                                          |                        |
| IncGeo_BoroughCode                     | E09000003              | Borough Code                                                            |                        |
| IncGeo_BoroughName                     | BARNET                 | Borough Name                                                            |                        |
| ProperCase                             | Barnet                 | Borough Name                                                            |                        |
| IncGeo_WardCode                        | E05000049              | Ward Code                                                               |                        |
| IncGeo_WardName                        | EAST FINCHLEY          | Ward Name                                                               |                        |
| IncGeo_WardNameNew                     | EAST FINCHLEY          | New Ward Name                                                           |                        |
| Easting_m                              | 527184                 | Easting                                                                 | redacted for Dwellings |
| Northing_m                             | 189488                 | Northing                                                                | redacted for Dwellings |
| Easting_rounded                        | 527150                 | Easting rounded up to nearest 50                                        |                        |
| Northing_rounded                       | 189450                 | Northing rounded up to nearest 50                                       |                        |
| Latitude                               | 51.58990022            | Latitude                                                                | redacted for Dwellings |
| Longitude                              | -0.165452578           | Longitude                                                               | redacted for Dwellings |
| FRS                                    | London                 | Fire Service ground                                                     |                        |
| IncidentStationGround                  | Finchley               | LFB Station ground                                                      |                        |
| FirstPumpArriving_AttendanceTime       | 348                    | First Pump attendance time in seconds                                   |                        |
| FirstPumpArriving_DeployedFromStation  | Finchley               | First Pump deployed from station                                        |                        |
| SecondPumpArriving_AttendanceTime      |                        | Second Pump attendance time in seconds                                  |                        |
| SecondPumpArriving_DeployedFromStation |                        | Second Pump deployed from station                                       |                        |
| NumStationsWithPumpsAttending          | 1                      | Number of stations with pumps in attendance                             |                        |
| NumPumpsAttending                      | 1                      | Number of pumps in attendance                                           |                        |
| PumpCount                              | 1                      |                                                                         |                        |
| PumpMinutesRounded                     | 1                      | Time spent at incident by pumps, rounded up to 60 if less than an hour |                        |
| Notional Cost (£)                      | 328                    | Time spent multiplied by notional annual cost of a pump                 |                        |
| NumCalls                               | 1                      | Number of calls received about the incident                             |                        |


## London's daily weather data

- [Source](https://www.kaggle.com/datasets/zongaobian/london-weather-data-from-1979-to-2023/data)
- Time span: 1979 to 2023
- Contents
    - DATE: Date in YYYYMMDD format.
    - TX: Daily maximum temperature in 0.1°C.
    - TN: Daily minimum temperature in 0.1°C.
    - TG: Daily mean temperature in 0.1°C.
    - SS: Daily sunshine duration in 0.1 hours.
    - SD: Daily snow depth in 1 cm.
    - RR: Daily precipitation amount in 0.1 mm.
    - QQ: Daily global radiation in W/m².
    - PP: Daily sea level pressure in 0.1 hPa.
    - HU: Daily relative humidity in %.
    - CC: Daily cloud cover in oktas.

- Each parameter includes an associated quality code:
    - 0: Valid data
    - 1: Suspect data
    - 9: Missing data
- Reference:
    - Klein Tank, A.M.G. and Coauthors, 2002. Daily dataset of 20th-century surface air temperature and precipitation series for the European Climate Assessment. International Journal of Climatology, 22, 1441-1453.
    - Data and metadata are available at http://www.ecad.eu.