# Documentation for themistor/SIPM heat dissipation studies

## Purpose:
- Analysis of data collected via thermistors of the heating gradient of the SIPM module. Heat was generated by running 1.04 W of power through each side of the SIPM module in order to model the predicted dark current production within the detector itself.

## Description of included files:

**thermistor_temp_plots**
- Accepts raw csv datasets from the raspberry pi and converts the ADC values into temperature plots
- Contains a basic normalization function accurate for the current iteration of the box
- Includes running average plotting, as well as returning the average value of a single thermistor over a set period of time
Use for: plotting thermistor temperature readings versus time

**CSV_Datasets**
- A folder to contain all raw .csv files retrieved from the SQL database using Data2Csv.py. 

