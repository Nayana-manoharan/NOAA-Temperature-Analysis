# NOAA-Temperature-Analysis

Project Overview

This project analyzes NOAA temperature data near Ann Arbor, Michigan, from 2005 to 2015. It visualizes record high and low temperatures, highlights extreme events in 2015, and maps weather stations in the region.


Dataset

The data comes from the National Centers for Environmental Information (NCEI) [Daily Global Historical Climatology Network (GHCN-Daily)] and consists of:

temperature.csv: Temperature observations (2005-2015)

BinSize.csv: Weather station details


Installation

Ensure you have the required libraries installed:

pip install pandas numpy matplotlib seaborn geopandas shapely folium


Usage

Run the script to generate visualizations:

python temperature_analysis.py


Outputs:

1. Familiarize yourself with the dataset, then write some python code which returns a line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day should be shaded.
2. Overlay a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.
3. Watch out for leap days (i.e. February 29th), it is reasonable to remove these points from the dataset for the purpose of this visualization.
4. Consider issues such as legends, labels, and chart junk.
5. The data you have been given is near **Ann Arbor, Michigan, United States**, and visualize on map the stations the data.
6. Plot Temperature Summary near Ann Arbor, Michigan, United States (Year 2015).
