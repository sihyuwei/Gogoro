# Gogoro

## Project Description
This repo is dedicated to obtain the data from a user-written database of Gogoro battery stations. (https://mowd.tw/gostation/)

## Original Data
The original data is downloaded from the map here (https://mowd.tw/gostation/map/).

## How to recreate the results
1. Download the the xml file from https://mowd.tw/gostation/map/.
2. Convert the data to the csv format using QGIS or other softwares. (as saved in the folder `intermediate`)
3. Run `scraping_websites.ipynb`. This code scrapes the information of the battery stations from their individual html websites.
4. Run `cleaning_battery_stations.ipynb`. This code cleans the content of the raw data, and extracts the activation times and deactivation times.
