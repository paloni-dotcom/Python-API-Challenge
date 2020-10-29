# Python-API-Challenge- What's the Weather like?

## WeatherPy

In this example, I created a Python script to visualize the weather of 500+ random (non-repeating) cities across the world of varying distance from the equator. I have used a simple Python library- citipy- and the OpenWeatherMap API, to create a representative model of weather across world cities and performing a weather check on each of the cities using a series of successive API calls.

The two objectives of this exercise are:

### 1. Generate various scattered plots showing correlation between:
* [Latitude vs Temperature](#Latitude_vs_Temperature)
* [Latitude vs Humidity](#Latitude_vs_Humidity)
* [Latitude vs Cloudiness](#Latitude_vs_Cloudiness)
* [Latitude vs WindSpeed](#Latitude_vs_WindSpeed)

### 2. Run Linear Regression for Northern and Southern Hemisphere for:
* [Northern Hemisphere - Temperature (F) vs. Latitude](#northern hemisphere-temperature vs latitude)
* [Southern Hemisphere - Temperature (F) vs. Latitude](#southern hemisphere-temperature vs latitude)
* [Northern Hemisphere - Humidity (%) vs. Latitude](#northern hemisphere-humidity vs latitude)
* [Southern Hemisphere - Humidity (%) vs. Latitude](#southern hemisphere-humidity vs latitude)
* [Northern Hemisphere - Cloudiness (%) vs. Latitude](#northern hemisphere-cloudiness vs latitude)
* [Southern Hemisphere - Cloudiness (%) vs. Latitude](#southern hemisphere-cloudiness vs latitude)
* [Northern Hemisphere - Wind Speed (mph) vs. Latitude](#northern hemisphere-wind speed vs latitude)
* [Southern Hemisphere - Wind Speed (mph) vs. Latitude](#southern hemisphere-wind speed vs latitude)

### Scattered Plots

#### Latitude_vs_Temperature
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig1.png" width=270></td>
  <tr>
<table>
* Above plot shows that temperatures are higher as you get closer to the equator. 

#### Latitude_vs_Humidity
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig2.png" width=270></td>
  <tr>
<table>
* Above plot shows that humidity is relatively consistant across all latitudes. 
    
#### Latitude_vs_Cloudiness
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig3.png" width=270></td>
  <tr>
<table>
* Above plot shows that cloudiness is relatively consistant across all latitudes.
    
#### Latitude_vs_WindSpeed
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig4.png" width=270></td>
  <tr>
<table>
* Above plot shows that Wind Speed is somewhat indiffernt to the latitudes but if you notice that Wind Speed outliners all are at latitudes furthest from equator. 
    
### Linear Regrissions

#### Northern Hemisphere - Temperature (F) vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig5.png" width=270></td>
  <tr>
<table>
    
#### Southern Hemisphere - Temperature (F) vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig6.png" width=270></td>
  <tr>
<table>

#### Northern Hemisphere - Humidity vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig7.png" width=270></td>
  <tr>
<table>
 
#### Southern Hemisphere - Humidity vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig8.png" width=270></td>
  <tr>
<table>
    
#### Northern Hemisphere - Cloudiness vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig9.png" width=270></td>
  <tr>
<table>
    
#### Southern Hemisphere - Cloudiness vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig10.png" width=270></td>
  <tr>
<table>
    
#### Northern Hemisphere - Windspeed vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig11.png" width=270></td>
  <tr>
<table>
    
#### Southern Hemisphere - Windspeed vs. Latitude
<table>
  <tr>
    <td><img src="WeatherPy/Images/fig12.png" width=270></td>
  <tr>
<table>
    
