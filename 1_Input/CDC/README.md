# Proj1_Grp2:  WANGRY
## CDC Folder content description

This folder contains the datasets extracted from the Centers for Disease Control and Prevention:  National Environment Public Health tracking Network

url:  https://ephtracking.cdc.gov/DataExplorer/index.html?

The website contains drinking water data from community water systems, including contaminantss.  Specifically, the data exported from the website is 2016 data from counties throughout the US, indicating weather the county was greater than the accepted mean concentration levels for the contaminants.

The zip files are the exact files exported, with actual measurement/contaminant appended to the file name
The csv files are the csv data files within the zip file and renamed to identify the contaminant and make data extraction easier in the python code

Even though the website seem to provide an API URL for each query, unfortunately, it seems that the server listed in the URL is no longer available to be accessed.