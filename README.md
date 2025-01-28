# Bike Sharing - BoomBikes 
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company wants to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands
- We are using a dataset with filename 'day.csv'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. The company should focus on increasing the demand for shared bikes during the fall season as it has the highest percentage of rental bikes.
2. The company should focus on increasing the demand for shared bikes during clear_partly_cloudy weather as it has the highest percentage of rental bikes.
3. The company should focus on increasing the demand for shared bikes on friday as it has the highest percentage of rental bikes.
4. The company should focus on increasing the demand for shared bikes in august as it has the highest percentage of rental bikes.
5. The company should focus on increasing the demand for shared bikes during the year 2019 as it has a high coefficient value.
6. The company should focus on increasing the demand for shared bikes during high temperature as it has a high coefficient value.
7. The company should focus on increasing the demand for shared bikes during light_snow_rain weather as it has a high coefficient value.
8. The company should focus on increasing the demand for shared bikes during the year 2019 as it has a high coefficient value.
9. The company should focus on increasing the demand for shared bikes during high temperature as it has a high coefficient value.
10. The company should focus on increasing the demand for shared bikes during light_snow_rain weather as it has a high coefficient value.

The company should focus on increasing the demand for shared bikes during the fall season, clear_partly_cloudy weather, friday, august, year 2019, high temperature and light_snow_rain weather.

### The Equation of Best Fitted Line is:

**cnt** = 0.2 + 0.23 x yr − 0.06 x holiday + 0.04 x workingday + 0.57 x temp − 0.17 x hum − 0.19 x windspeed + 0.08 x season_summer + 0.13 x season_winter − 0.04 x mnth_january − 0.04 x mnth_july + 0.09 x mnth_september + 0.05 x weekday_saturday − 0.24 x weathersit_light_snow_rain − 0.05 x weathersit_mist_cloudy



- **R-squared value**: 0.81
- **Adjusted R-squared value**: 0.79 
- **RMSE value**: 0.1  

The model is a good fit for the data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
    Pandas Version : Pandas 2.2.2
    Numpy Version : Numpy 1.26.4
    Seaborn Version : Seaborn 0.13.2
    Matplotlib Version : Matplotlib 3.8.4
    Sklearn Version : Sklearn 1.4.2
    Warnings Version  : 0.1.0
    Python Version : Python 3.7.6

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@raghavmishrad365] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
