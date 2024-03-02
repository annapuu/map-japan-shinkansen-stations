# Shinkansen Stations in Japan (Python & Tableau)

With this project I wanted to combine two interests of mine: Japan and maps. On kaggle, I quickly found this dataset on shinkansen stations and decided to use it, combining python for the data preparation and tableau for the visualization.

As the dataset did not have an address or coordinates for the stations, I saw on kaggle that someone had used the library geopy to get the coordinates. I had never done that before, so I decided to give it a try. After some difficulties in trying to use the suggested geocoder Nominatim, which gave an SSL error which I couldn't resolve in a way and time I hoped to, I tried using another one and ended up succesfully using Bing as my third try (the second one didn't give any correct coordinates).

## Files

- Shinkansen_stations_inJapan.csv: the initial dataset from kaggle
- Japan_Shinkansen_Stations_2023.html: short data preparation and geolocating the coordinates for the stations using geopy (python)
- Shinkansen_stations_inJapan_geo.csv: saved dataset with new columns for latitude and longitude

## Libraries

- pandas
- geopy
- folium
